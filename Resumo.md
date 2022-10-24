# Resumo Git/Github: :books: :writing_hand:

### Comandos Git:

- Local especifico: cd + nome da pasta

- Voltar um nível de navegação: cd ..

- Lista de pastas: ls / dir

- Criar pastas/arquivos: mkdir

- Deletar pastas/arquivos: delete

- Limpar a tela: ctrl+l

- Tecla Tab completa a escrita

-  Seta para cima mostra comandos dados

- Mover arquivos: mv + nome ./local/

  



### Como criar uma pasta:

Usando o comando mkdir digite o nome da nova pasta, de um enter.



### Como criar um arquivo:

Para criar um arquivo direto no terminal, dentro da pasta, use o comando echo junto com o sinal > escreva o nome do arquivo . e o formato (txt, md ...) e de um enter.



### Excluir um arquivo

Usar o del + nome do arquivo. Esse comando apenas deleta o arquivo.



### Excluir um pasta

Para excluir uma pasta com todos os arquivos dentro é utilizado o rmdir + o nome da pasta mais duas flegles /S /Q e aperta enter.



### Criando um repositório

Quando usando git init cria um repositório 

### Versonando o código

Para iniciar o versonamento com o comando git  init e dar enter. Esse comando cria uma pasta oculta chamada .git, para visualizar essa pasta usar a flegle -a que mostra arquivos ocultas.  



### Comitando um arquivo

Usar git add * e apertar enter, em seguida usar git commit -m e passar um texto (mensagem que é carregada junto) entre "" e dar enter. Ele passa a integrar o repositório local e pode ser empurrado.



### Git status 

O git status ajuda a saber os estado do arquivo e até mesmo o que precisa ser feito com ele, para utilizar basta digitar git status e dar enter. 





### Empurrado arquivo 

Para empurrar um arquivo para o github, abrir o arquivo, digitar git remote add origin + link criado no github. Usando git remote -v ele lista os repositórios remoto. Para empurra o arquivo digitar git push origin master ou main, dar enter.



### Puxando um arquivo

Para puxar um arquivo de repositório remoto para seu pc, git push origin master ou main.



### Clonar

Para baixar um repositório,  copiar o link do github, digitar git clone mais a url





