install-pgadmin-4-desktop-linux
=========

Role do Ansible para a instalação do pgAdmin 4 em Distribuições Linux


Distribuições Suportadas pela Role
------------
- Fedora 37 ou superior
- Linux Mint 21.1 ou superior
- Ubuntu 22.10 ou superior


Dependências da Role 
--------------

Debian, Linux Mint e Ubuntu:

- openssh-server. Ex.: sudo apt install openssh-server


Exemplo de Playbook
----------------

Exemplo de uso da Role, com as configurações padrão:

    - hosts: desktop
      roles:
         - install-pgadmin-4-desktop-linux


Exemplo de Comandos
----------------

Comando para executar todas as tasks:

    ansible-playbook -i <caminho_inventario> <caminho_playbook>


License
-------

MIT License