# Curso_git

Aprendendo git

## Comandos fundamentais

* _Introdução da seção_

## O que é um repositório?

É onde o código será **armazenado**;
Na maioria das vezes cada projeto tem **um repositório**;
Quando criamos um repositório estamos iniciando um projeto;
O repositório pode ir para servidores que são especializados em gerenciar repos, como:**GitHub** e **Bitbucket**;
Cada um dos desenvolvedores do time pode baixar o repositório e **criar versões diferentes** em sua máquina;

## Criando repositórios

Para criar um repositório utilizamos o comando:**git init**
Desta maneira o git vai criar os arquivos necessários para iniciallizá-lo;
Que estão na pasta oculta **.git**;
Após este comando o diretório atual **será reconhecido pelo git como um projeto** e responderá aos seus demais comandos;

## O que é o GitHub?

É um **serviço para gerenciar repositórios**, gratuito e amplamente utilizado;
Podemos **enviar nossos projetos** para o GitHub e disponibilizá-lo para outros devs;
O GitHUb é gratuito tanto para projetos públicos como **privados**;
Vamos criar uma conta em:<https://github.com>

## Mudança do nome principal de branch

Olá pessoal!

Há um tempo atrás houve uma mudança no GitHub, o branch principal se chamava master e agora se chama main, então pode ser que haja essa diferença de nomenclatura ao longo do curso, você só precisa trocar onde estiver master para main.

Na prática não muda em nada, é apenas uma alteração de nomenclatura, inclusive podemos criar o nosso repositório com o nome de master como o branch principal, isso é configurável e permitido. O que acontece é que a sugestão feita pelo GitHub como branch principal agora tem o nome de main.

Um abraço a todos!

## Enviando repositório para o GH

Podemos facilmente **enviar nossos repos** para o GitHUb;
Precisamos criar o projeto no GitHub, inicializar o mesmo no git em nossa máquina, sincronizar com GH e enviar;
E esta sequência que parece ser complexa é facilmente executada **por poucos comandos**;
Vale lembrar que só fazemos **uma vez por projeto** este fluxo;
Porém alguns dos comandos utilizados vão ser úteis ao longo do curso;

## Comandos do git

## ...Or create a new repository on the command line

echo "# curso_git" >> README.md

git init

 1º git add README.md

2º git commit -m "first commit"

3º git push -u origin master

git branch -M master - para criar uma branch

## adcionando uma origem

tem duas formas -> 

git remote add origin <git@github.com:maxsanttos/Curso_git> 

git  remote add origin <https://github.com/maxsanttos/Curso_git>
____________________________________________

## Remover a origem atual

git remote -v - ver as origins

git remote rm origin - para remover
_____________________________________________
