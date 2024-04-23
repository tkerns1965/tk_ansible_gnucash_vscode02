# tk_ansible_gnucash_vscode02

For use on bare Debian 12 Desktop

1.  sudo apt install -y ansible git
2.  git clone https://github.com/tkerns1965/tk_ansible_gnucash_vscode02.git
3.  cd tk_ansible_gnucash_vscode02/
4.  copy private.yml to roles/gnucash_vscode/vars/
5.  ansible-playbook -K gnucash_vscode.yml