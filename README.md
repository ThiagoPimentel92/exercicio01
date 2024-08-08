# exercicio01

Comandos


### Inicializa Git na pasta atual ###

   git init

#### Configura o nome de usuário global ###

git config --global user.name "Thiago.pmentel"

### Configura o email de usuário global ###

git config --global user.email "thiago.pimentel92@gmail.com"

### Criacao repositorio ###

1 - mkdir exercicio01

### Acessar repositório ### 

2 - cd exercicio01 

### Criar arquivo.txt ### 

4 - echo 01 > arquivo.txt

### Adicionar o arquivo no staging ### 

5 - git add arquivo.txt

### Conferir o status ### 

6 - git status

### Commitar o arquivo do staging com a descrição "git add example - arquivo.txt“  ### 

7 - git commit -m "git add example - arquivo.txt"

### Sobrescrever o conteúdo do arquivo.txt: ### 

8 - echo 02 > arquivo.txt

### Verificar o diffing no arquivo ### 

9 - git diff

### Adicionar novamente o arquivo no staging  ### 

10 - git add arquivo.txt

### Conferir o status ### 

11 - git status

### Verificar o diffing no arquivo ### 

12 - git diff --staged

### Sobrescrever o conteúdo do arquivo.txt: ### 

13 - echo  03 > arquivo.txt

### Verificar o diffing no arquivo  ### 

14 - git diff

### Fazer o restore do arquivo da área de staging ### 

15 - git restore --staged arquivo.txt

### Verificar o status ### 

16 - git status

### Realizar o commit do arquivo ### 

17 - git commit -m "add exemple - arquivo.txt"

### Verificar o log ### 

18 - git log

### Adicionar um arquivo gitignore com o seguinte conteúdo: *.txt ### 

19 - echo "*.txt" >> .gitignore 

### Criar um arquivo novo.txt ### 

20 - echo new > novo.txt

### Verificar o status  ### 

21 - git status
    
