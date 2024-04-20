# tk_ansible_gnucash_vscode02

For use on bare Debian 12 Desktop

<!-- 1.  sudo apt-add-repository -y ppa:ansible/ansible -->
2.  sudo apt install -y ansible git
<!-- 2.  sudo apt install -y ansible git python-pexpect -->
3.  git clone https://github.com/tkerns1965/tk_ansible_gnucash_vscode02.git
4.  cd tk_ansible_gnucash_vscode02/
5.  cp roles/gnucash_vscode/vars/private.yml.sample roles/gnucash_vscode/vars/private.yml
6.  nano roles/gnucash_vscode/vars/private.yml
7.  ansible-playbook -K gnucash_vscode.yml