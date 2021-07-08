# WSL2 HOST

Esse script foi desenvolvido com o intuito de possibilitar e facilitar o uso da plataforma [**Expo**](https://expo.io/) com o **WSL2**.

O criador deste script é o usuário [**jonhoffmam**](https://github.com/jonhoffmam/)

**O que o script faz**❔

- Busca o IP da interface a ser utilizada (ex.: Ethernet, Wi-Fi) na máquina local (Windows) e na máquina remota (WSL2);
- Abre as portas **19000,19001,19002,19003,19004,19005** no firewall do Windows;
- Faz o direcionamento entre endereço IP local (Windows) e endereço IP remoto (WSL2);
- Insere a variável de ambiente **```REACT_NATIVE_PACKAGER_HOSTNAME```** nos arquivos **```.bashrc```** e **```.zshrc```** caso exista;
- A variável de ambiente **```REACT_NATIVE_PACKAGER_HOSTNAME```** recebe automaticamente o endereço IP da máquina local (Windows);
- Com isso, é possível criar uma tarefa agendada no Windows para executar o script a cada logon.
