# Cisco IOS Ansible Template
Cisco IOS configuration mainly based on IOS hardening guide by Cisco (https://www.cisco.com/c/en/us/support/docs/ip/access-lists/13608-21.html) and Center for Internet Security Cisco IOS 15 Benchmark v4.0.0

## Usage
- Edit global defaults in "roles/Cisco_IOS/defaults/main.yml" to your liking
- Add IOS devices with site and device specific configuration in inventory
- Run "ansible-playbook site.yml -i inventory" to generate the configurations which will be placed in a directory named "configs"
