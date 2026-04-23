# Dicionário Comandos Linux


## **Introdução**

Neste trabalho serão apresentados 30 comandos essenciais do Linux em espécie de dicionário. Os comandos serão apresentados com sua principal função e exemplo de como é utilizado pelos usuários do sistema operacional Linux. Desta forma, o objetivo é apresentar de forma clara quais comandos estão presentes no Linux e como são utilizados para que o usuário possa ter clareza de seu funcionamento. 

## **Comandos Linux**

### Comandos para Manipulação de Diretório 
`ls` - Este comando listará os arquivos do diretório.
> Exemplo: ls/home/username/documents (Para visualizar outros repositórios é preciso adicionar o caminho do diretório após "ls")

`cd` - Este comando permite entrar em diretórios e modificá-los, sendo necessária permissão de execução para entrar no diretório.
> Exemplo: cd/home/username/documents

`pwd` - Este comando mostrará o nome e o caminho do diretório atual, também podendo ser utilizado para verficiar em qual diretório está. 
> Exemplo: pwd (Exibirá o diretório atual)

`mkdir` - Este comando criará um ou mais diretórios no sistema.
> Exemplo: mkdir novo_diretorio

`rmdir` - Este comando removerá um diretório do sistema, sendo necessário o diretório estar vazio e a permissão de gravação para que o usuário possa removê-lo. 
> Exemplo: rdmir [opções] 

### Comandos Para Manipulação de Arquivos 
`cat` - Este comando mostrará o conteúdo de um arquivo binário ou texto. 
> Exemplo: cat texto.txt 

`tac` - Este comando mostrará o conteúdo de um arquivo binário ou texto, em ordem inversa. 
> Exemplo: tac file-all.txt

`rm` - Este comando apagará arquivos.
> Exemplo: rm teste.txt (Apagará o arquivo 'text.txt' no diretório atual)

`cp` - Este comando copiará arquivos. 
> Exemplo: cp teste.txt teste1.txt (Copiará o arquivo 'teste.txt' para 'teste1.txt')

`mv` - Este comando move ou renomeia arquivos e diretórios. Sendo semelhante ao comando 'cp', no entanto o arquivo de origem será apafado após o fim da cópia.  
> Exemplo: mv teste.txt teste1.txt (Muda o nome de 'teste.txt' para 'teste1.txt')

### Comandos de Rede
`who` - Este comando mostrará quem está atualmente conectado no computador, listando os nomes dos usuários que estão conectados no computador.
> Exemplo: who [opções] - who -H (Mostrará o cabeçalho das colunas)

`telnet` - Este comando permitirá o acesso a um computador remoto. Será mostrada uma tela de acesso correspondente ao computador local, no qual é necessário a autenticação do usuário para acessar o sistema. 
> Exemplo: telnet [opções][ip/dns][porta] ('Opções' pode variar de acordo com a necessidade do usuário, 'ip/dns' é o endereço IP do computador de destino ou nome DNS e 'porta' é onde será feita a conexão)

`finger` - Este comando mostrará detalhes sobre os usuários do sistema. 
> Exemplo: finger [usuário][usuário@host] ('Usuário' é o nome do usuário que se deseja obter detalhes do sistema e 'usuário@host' é o nome do usuário e o endereço do computador que se deseja obter detalhes)

`whoami` - Este comando mostrará o nome que foi utilizado para se conectar ao sistema.
> Exemplo: whoami (O comando é executado sozinho) 

`talk` - Este comando iniciará uma conversa em tempo real com outro usuário de sistema em uma rede local ou na Internet.
> Exemplo: talk [usuário][tty] ('Usuário' é o nome de login do usuário que deseja iniciar uma conversa e 'tty' é o nome de terminal onde o usuário está conectado para iniciar uma conexão local)

### Outros comandos 

`clear` - Este comando limpa a tela e posiciona o cursor no canto superior esquerdo.
> Exemplo: clear (O comando é executado sozinho, assim que apertado "enter" toda a saída anterior desaparece)

`ln` - Este comando cria links para arquivos e diretórios no sistema.
> Exemplo: ln -s /deve/ttyS1 /dev/modem (Cria um link para o arquivo)

`find` - Este comando procura um arquivo ou um diretório no disco através de sua data de modificação, tamanho, entre outros fatores.
> Exemplo: find/home/teste -name "documento.txt" (O comando procura dentro da pasta /home/teste um arquivo chamado documento.txt)

`dmesg` - Este comando mostra as mensagens de inicialização do kernel.
> Exemplo: dmesg (O comando exibe apenas mensagens relacionadas as dispositivos USB)

`wc` - Este comando conta o número de palavras, bytes e linhas em um arquivo ou entrada padrão.
> Exemplo: wc -w /etc/passwd (Mostra a quantidade de palavras do arquivo /etc/passwd.

`diff` - Este comando compara dois arquivos e mostra a diferença entre eles.
> Exemplo: diff texto.txt texto1.txt (Com o arquivo texto.txt com texto1.txt e exibe suas diferenças na tela)

`shutdown` - Este comando deliga/reinicia o computador imediatamente ou após determinado tempo de maneira segura.
> Exemplo: shutdown -h now (Desliga o computador imediatamente)

`chattr` - Este comando modifica atributos de arquivos e diretórios.
> Exemplo: chattr = teste.txt (Retira todos os atributos)

`touch` - Este comando modifica a data e a hora que um arquivo foi criado.
> Exemplo: touch -t 10011230 teste (Altera a data e a hora do arquivo para 01/10 e 12:30)

`free` - Este comando mostra detalhes sobre a utilização da memória RAM do sistema.
> Exemplo: free (Mostra um resumo da memória em kilobytes)

`uptime` - Este comando mostra o tempo de execução do sistema desde que o computador foi ligado.
> Exemplo: uptime (Mostra automaticamente informações do computador)

`head` - Este comando mostra as linhas iniciais de um arquivo de texto.
> Exemplo: head n- 5 documento.txt (Mostra as 5 primeiras linhas do arquvido documento.txt)

`echo` - Este comando exibe mensagens.
> Exemplo: echo "olá, mundo" (A saída será "olá, mundo")

`reboot` - Este comando reinicia o computador.
> Exemplo: reboot (ocorre de maneira automática)

`hostname` - Este comando mostra ou muda o nome de seu computador na rede.
> Exemplo: hostname (teste-pc o nome da máquina configurado no sistema)

## **Conclusão**
Portante, é possível concluir que os comandos do Linux fornecem uma grande flexibilidade para o usuário, em que permitem desde a navegação entre diretórios até o monitoramento do sistema. O estudo dos mesmos é fundamental pois são a base para controlar um sistema de maneira eficiente, principalmente em servidores que não possuem interface gráfica; conhecer os comandos é uma habilidade prática que contribui para para organização e controle em ambientes de trabalho e estudo. 
