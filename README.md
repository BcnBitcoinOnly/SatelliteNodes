# SatelliteNodes

SatelliteNodes is an Ansible playbook for automating the deployment of Bitcoin Core on Debian 11 machines. It simplifies the process of setting up and configuring a Bitcoin node by handling the installation and configuration of the necessary dependencies and software.

The repository includes an Ansible role for installing and configuring Bitcoin Core, which can be customized to suit your specific needs. The playbook downloads the latest version of Bitcoin Core from the official website and configures it with a custom \`bitcoin.conf\` file. Once the installation and configuration are complete, the \`bitcoind\` daemon is started and the Bitcoin node is ready to use.

SatelliteNodes is perfect for developers and enthusiasts who want to run their own Bitcoin nodes on Debian 11 machines without having to go through the tedious process of manual installation and configuration. By using SatelliteNodes, you can save time and effort and focus on your Bitcoin projects instead.

## Features

- Easy to use Ansible playbook for deploying Bitcoin Core on Debian machines.
- Customizable Ansible role for installing and configuring Bitcoin Core to suit your specific needs.
- Automatic download and installation of the latest version of Bitcoin Core from the official website.
- Configures Bitcoin Core with a custom \`bitcoin.conf\` file.
- Starts the \`bitcoind\` daemon automatically, so your Bitcoin node is ready to use.

## Usage

To use SatelliteNodes, you'll need to have Ansible installed on your local machine. You should also have a group of Debian 11 machines defined in your Ansible inventory.

1. Clone this repository to your local machine.

2. Customize the \`playbook.yml\` file to suit your needs, such as changing the version of Bitcoin Core or adding custom configuration options.

3. Run the following command to deploy Bitcoin Core on your Debian 11 machines:

   ```
   ansible-playbook -i inventory.ini playbook.yml
   ```

   Make sure to replace `inventory.ini` with the path to your Ansible inventory file.

For more detailed instructions, please refer to the `README.md` file.

## License

SatelliteNodes is released under the GNU General Public License. See the `LICENSE` file for more information.
