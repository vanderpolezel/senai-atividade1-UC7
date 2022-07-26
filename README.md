# senai-atividade1-UC7

Apresentação dos Principais comandos aprendidos e estudados

1. git config --global user.name "Vander Michellao" /*configurando o nome do usuário que acessando

2. git config --global user.email "vander.michellao@gmail.com" /*configurando o nome do email que acessando

3. git config user.e-mail /*mostra as informações do e-mail adicionada

4. git config user.name /*mostra as informações do nome adicionado

5. git init /*Inicializou e criou a pasta oculta .git

6. git add nome do arquivo /*adicionou um arquivo em especifico*/

7. git add . /*adiciona todos arquivos dentro da pasta para serem salvas*/

8. git status /*mostra o status dos arquivos*/

9. git commit -m "Cirando arquivo index.html com lista de cursos" /*é o ato de salvar as modificações feitas o -m precisa para especificar a mensagem do commit. O git monitora linha a linha do arquivo que foi salvo.*/

10. git status /*vai mostrar o status das alterações*/

11. git add index.html /*adicionado arquivo em específico para a Staging*/

12. git add . /* adicionando todos os arquivos para a Staging que estão na pasta, menos os que estão adicionados no .gitignore*/

13. git commit -m "Acento adicionado no curso de Integração Continua" */

14. git log /*mostra o Hash a indentificação unica do commit e o ramo que o commit se encontra, autor, data e mensagem do commit.

15. git log --online /*mostra cada commit em uma única linha.*/

16. git log -p   /*visualiza as alterações do commit*/

17. git log --pretty="format:%H"--- /*mostra somente o hash*/

18. git log --pretty="format:%h %s %ae  /*mostra o hast resumendo a mensagem do commit, o autor*/

/*criei um arquivo naomonitorar.txt/*

19. git status  /*mostra como um arquivo novo do projeto.*/

20. .gitignore  /* ao adicionar os arquivos dentro do .gitignore não seram monitorados pelo git */

/*Compartilhando o projeto no GitHun - Criando um repositório Remoto */

21. git remote add origin https://github.com/vanderpolezel/senai-atividade1-UC7.git

22. git remote add local c:/Users/Alura/Documents/git-e-github/servidor/ /*Adicionado meu repositório remoto*/

23. git remote -v /* mostra as informações do repositório remoto */

24. git clone /*Faz uma copia completa do projeto*/

25. git push -u origin master /* envia os dados para o Servidor Remoto, primeiro acesso pede login e senha do github*/

26. git pull /*Pega os dados do Servidor Remoto*/

27. git branch novobranch /*Criou um banch nova com o nome novobranch */

28. git checkout novobranch /*acesso o novobranch*/

29. git checkou -b novobranch /* Já cria o novobranch e acessa o mesmo*/

30. git merge novobranch /*Cria o commit de junção de branches*/

31. git tag -a v1.0 -m "mensagem da tag" /*cria uma tag*/

32. git push orign --tags /*Empurra a tag para o respositório local*/

/*Comentários adicionais*/

/* HEAD: Estado atual do nosso código, ou seja, onde o Git os colocou
Working tree: Local onde os arquivos realmente estão sendo armazenados e editados
index: Local onde o Git armazena o que será commitado, ou seja, o local entre a working tree e o repositório Git em si.*/
