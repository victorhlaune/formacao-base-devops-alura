# Linux e DevOps
- DevOps surge como uma cultura de integração das equipes de Desenvolvimento e Operações:
    - Time de DEV entrega produto, Time de Operações pega o produto e leva para PRD, em alguma Infra;
    - A cultura DevOps surge como uma forma de melhorar a qualidade do software, automatizar e monitorar operações, realizar testes, integrações e entregas contínuas;

- O mundo de infra/web é "todo" baseado em Linux:
    - O SO é composto por módulos integrados, não é uma caixa fechada;
    - Tem o kernel como núcleo:
        - Componente central que conecta o software ao hardware do computador;
        - Gerencia os recursos do sistema, memória, processos e dispositivos;
        - Facilita a interação entre os componentes de hardware e software;
        - Garante que tudo esteja pronto para o uso do computador quando ele é ligado;
    - Uma máquina Linux pode ser acessada remotamente via protocolo SSH:
        - Precisa ter o endereço IP da máquina;

```shell
usuario@servidor:~$ sudo apt update 
    # sudo: executar tarefa como admin; 
    # apt: gerenciador de pacotes; 
    # update: verificar o que tem para atualizar;

usuario@servidor:~$ help 
    # lista comandos Shell

usuario@servidor:~$ ls  
    # lista tudo que está nos diretórios

usuario@servidor:~$ ls -a 
    # lista todos os arquivos + ocultos no diretório

usuario@servidor:~$ pwd 
    # responde em que diretório estamos

usuario@servidor:~$ mkdir <nome-do-diretorio> 
    # cria um diretório na pasta em que estamos com o nome passado

usuario@servidor:~$ cd <nome-do-diretorio> 
    # cd == change directory e avança para o diretório

usuario@servidor:~$ cd 
    # Por default só o cd volta para o home

usuario@servidor:~$ touch <nome-do-arquivo> 
    # Cria o arquivo

usuario@servidor:~$ cat > <nome-do-arquivo> 
    # Adicionando valor ao arquivo
    <Digite o texto aqui> # Digita o texto que quer inserir no arquivo; Para sair da escrita: CRTL + D

usuario@servidor:~$ cat <nome-do-arquivo> 
    # Faz a leitura do arquivo

usuario@servidor:~$ echo <mensagem> 
    # Exibe a mensagem 

usuario@servidor:~$ echo <texto> > <nome-do-arquivo> 
    # Inserir o texto ao arquivo

usuario@servidor:~$ mv <arquivo> <diretorio> 
    # para mover o arquivo para outro diretório

usuario@servidor:~$ tar -czf <nome-do-arquivo>.tar.gz <arquivos-que-quero-compactar> 
    # c==criar z==zip f==file(nome-do-arquivo)
	# exemplo: tar -czf compactado.tar.gz arquivo_1.txt arquivo_2.txt

usuario@servidor:~$ rm <arquivo> 
    # para remover o arquivo
```