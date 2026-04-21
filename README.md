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

## **Conclusão**
> idsfhjisjdfes
