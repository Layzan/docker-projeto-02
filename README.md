# Welcome to ![Vagrant](https://img.shields.io/badge/-Vagrant-333333?style=flat&logo=vagrant&logoColor=117AF7)



## 📌 Inicializar

**>> vagrant init nome_box**

Este comando cria o arquivo Vagrantfile.
Exemplo:

**>> vagrant init **_ubuntu/trusty64_****

## 📌 Subir uma VM

**>> vagrant up**

Se no seu script tiver mais de uma máquina e você quiser subir somente uma:

**>> vagrant up nome_vm**

Este comando serve para os demais exemplo, se quiser especificar a VM basta colocar o comando e em seguida o nome da máquina.

## 📌 Parar

**>> vagrant halt**

## 📌 Destruir

**>> vagrant destroy -f**

## 📌 Reiniciar

**>> vagrant reload**

Este comando reinicia a VM e reavalia o Vagrantfile para instalação de novas dependências.

## 📌 Verificar o status

**>> vagrant status**

## 📌 Acesso remoto

**>> vagrant ssh nome_vm**

Acessa a instancia ativa, e se tiver mais de uma pode especificar com o nome da máquina.

