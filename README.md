# Roadmap

Esse Roadmap tem a finalidade de ser um guia para o aprendizado na área DevOps [Márcio Barborsa](https://github.com/marciorgb/Roadmap).


## Conteúdo

* Conhecimento essencial
	* [Sistemas Operacionais](#sistemas-operacionais)
	* [Redes](#redes)
	* [Unix](#unix) 
* Conhecimento desejável
	* [Segurança da Informação](#seguranca-da-informação) 
	* [Alta Disponibilidade](#alta-disponibilidade)
	* [Otimização de Recursos](#otimizacao-de-recursos)
* Ferramentas e Linguagens
	* [Python](#python)
	* [Git](#git)
	* [Ansible](#ansible)
	* [Docker](#docker)
	* [Kubernetes](#kubernetes)
	* [Editor](#editor)
* SoftSkills
	* [Comunicação](#comunicacao)
	* [Proatividade](#proatividade)
	* [Planejamento](#planejamento)
	* [Negociação](#negociacao)
* Fontes
	* [Livros](#livros)
	* [Sites](#sites)


## Conhecimento essencial

Deverá ter o conhecimento dos tópicos abaixo, com a capacidade de explicar a leigos e iniciantes da área.


### Sistemas Operacionais 

- [ ] [Processos](https://en.wikipedia.org/wiki/Process_(computing))
- [ ] [Threads](https://en.wikipedia.org/wiki/Thread_(computing))
- [ ] [Gerenciamento de Memória](https://en.wikipedia.org/wiki/Memory_management) 
	* Física
	* Virtual
- [ ] [Kernel Linux](http://www.guiafoca.org/cgs/guia/inic_interm/ch-kern.html)
- [ ] [Scheduling](https://en.wikipedia.org/wiki/Scheduling_(computing)) 
- [ ] [Use METHOD](http://brendangregg.com/usemethod.html)

### Redes

- [ ] TCP e UDP
- [ ] TCP/IP
- [ ] Redes Wan 
- [ ] Redes Lan
- [ ] Roteamento
	* IP
	* Mascara de rede
	* Sub Redes 
- [ ] Sockets 
- [ ] DNS
- [ ] Erros HTTP 

### Unix 

- [ ] [Ferramentas e comandos básicos](http://www.tldp.org/LDP/GNU-Linux-Tools-Summary/html/GNU-Linux-Tools-Summary.html) 
	* Nagevação
	* Controle de pastas e arquivos
	* Terminal virtual
	* Busca
	* Instalação de programas
	* Controle de sistema
- [ ] Comunicação de processos
- [ ] [Wildcards](http://www.tldp.org/LDP/GNU-Linux-Tools-Summary/html/GNU-Linux-Tools-Summary.html#WILDCARDS)
	* Backslash
- [ ] [Estrutura de diretórios](https://slashmedia.wordpress.com/2007/12/23/linux-directory-structure/)
- [ ] [Controles de terminal](http://www.tldp.org/LDP/GNU-Linux-Tools-Summary/html/GNU-Linux-Tools-Summary.html#other-key-combinations)
- [ ] [Muti comandos](www.tldp.org/LDP/GNU-Linux-Tools-Summary/html/GNU-Linux-Tools-Summary.html#performing-more-than-one-command)

## Conhecimento Desejável

### Segurança da informação

- [ ] Firewall
- [ ] Chaves SSH, GPG
- [ ] Criptografia
- [ ] Tipos de ataques
- [ ] Medidas corretivas a ataques 

### Alta disponiilidade

- [ ] Tipos de ataques
- [ ] Medidas Corretivas
- [ ] Balanceamento de carga 
- [ ] Controle de backup

### Otimização de Recursos

- [ ] Otimização de espaço em disco
- [ ] Otimização de blocos 
- [ ] Otimização baseado em diferenças entre a aplicação

## Ferramentas e Linguagens 
Dever ter a capacidade de expliocar comandos AD-HOC e também ser capaz de utilizar qualquer uma das ferramentas abaixo aplicando o que é proposto para a mesma a nível de Infra. 

### Python 

- [ ] Deve ser capaz de enter de fazer scripts em python
- [ ] Concluir o path de Python do [PluralSight](https://app.pluralsight.com/paths/skills/python)
- [ ] Melhorar suas skills no path anterior em 10%am

### Git

- [ ] [Conceitos básicos](https://en.wikipedia.org/wiki/Git)
	* O que é
	* Commits
	* Branches
	* Push
	* Merge
	* Repositórios
	* [Comandos](https://try.github.io/levels/1/challenges/1)
		* push
		* fetch
		* merge
		* commit 
		* push
- [ ] [Git flow](http://datasift.github.io/gitflow/IntroducingGitFlow.html)
- [ ] [Git lab](https://pt.wikipedia.org/wiki/GitLab)
- [ ] Chave GPG e assinatura de commits
- [ ] [CI e CD](https://www.atlassian.com/continuous-delivery/ci-vs-ci-vs-cd)

### Ansible

- [ ] [Conceito](https://www.ansible.com/resources/get-started)
	* O que é 
	* Porque usar
	* Como funciona
- [ ] Yaml
- [ ] AD-HOC
	* ansible-playbook
	* ansible-galax
- [ ] [Estrutura dos playbooks](http://docs.ansible.com/ansible/latest/playbooks_intro.html)
	* Roles
	* Vars
	* Defaults
	* Tasks
	* Group vars
	* Hosts
- [ ] Commandos playbook
	* name
	* hosts
	* src
	* dest 
	* apt
	* notify 
	* with_items
	* shell
	* template



- [ ] [Modulos](http://docs.ansible.com/ansible/latest/modules_by_category.html)
	* docker 
	* db

### Docker 

- [ ] [Conceitos básicos](https://docs.docker.com/get-started/)
	* Imagem
	* Conteiner
	* Conteiner vs VM
	* Root
- [ ] [AD-HOC](https://docs.docker.com/get-started/part2/)
	* images
	* image ls
	* ps
	* conteiner
	* run
		* it
		* -p 
		* -d
	* stop
- [ ] [Repository](https://hub.docker.com)
- [ ] [Dockerfile](https://docs.docker.com/get-started/part2/)
- [ ] [Requirements](https://docs.docker.com/get-started/part2/)
- [ ] [Docker swarm](https://docs.docker.com/get-started/part4/)

### Kubernetes

- [ ] [Conceitos básicos](https://kubernetes.io)
	* controle de balanceamento 
- [ ] Estrutura 
- [ ] [AD-HOC](https://kubernetes.io)
- [ ] Deploy
- [ ] [Integração com Docker](https://www.docker.com/kubernetes)
- [ ] [Integração com Ansible](http://docs.ansible.com/ansible/latest/kubernetes_module.html)

### Editor

- [ ] Ter o conhecimento de algum editor de texto completo 
	* [emacs](https://www.gnu.org/software/emacs/)
	* [vim](http://www.vim.org)
	* [sublime](https://www.sublimetext.com)
	* [visualstudio code](https://code.visualstudio.com)

## Soft Skills

###  Comunicação 

* Comunicação Objetiva e clara 
* Comunicação escrita
* Reports
* Saber explicar bem 

### Proatividade 

* Comunicação de problemas 
* Questionamento de dificuldades
* Busca de conteúdo

### Reconhecimento de capacidades

* Saber quando pedir ajuda 
* Entender limites

### Negociação

* Negociar prazos
* Conhecer os porquês durante a argumentaçao

### Planjeamento

* Priorizar atividades
* Definir deadlines

## Fontes 

### Livros

* [TANENBAUM] - A modern Operating Sistems  
* [TANENBAUM] - Redes de Computadores 

### Sites

* [Pluralsight](https://www.pluralsight.com)
