# Ansible Playbook for SoftEther VPN server

see **[SoftEther VPN Project](https://www.softether.org)**


## Requirement

- [Ansible](https://www.ansible.com) (`pip3 install ansible`)


### Server requirement

- OS: Ubuntu 20.04


## Usage

1. Update `./hosts`
    ```
    vi ./hosts
    ```
    You should change `your-server-host` to your     
2. Deploy
    ```sh
    ansible-playbook -i hosts vpn.yml
    ```
