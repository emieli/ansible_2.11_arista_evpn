# apt install git python3-pip python3-venv
# python3 -m venv venv
# source venv/bin/activate
# pip install --upgrade pip
# pip install ansible
# ansible-galaxy collection install arista.eos

### Arista config
username admin privilege 15 role network-admin secret <password>
management api http-commands
   no shutdown