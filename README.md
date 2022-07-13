# DESAFIO GIT/GITHUB DA DIO  ✅
Entendendo tudo sobre Git e GitHub

## O que é Git? 

Git é um sistema de **controle de versão de arquivos**. Ele é utilizado para a criação de um histórico de alterações em código-fonte de projetos de desenvolvimento de software. 

Por meio dele podemos desenvolver projetos, trabalhando em equipe com outros desenvolvedores ao mesmo tempo, sem correr o risco das aterações serem sobrescrita. Podemos saber quais foram as alterações realizadas, quem fez as alterações e baixar essas mudanças em nossa máquina. Também permite a recuperação de versões e códigos de forma segura, sem correr o risco de perder dados importantes.

## O que é GitHub?

O Github é uma **plataforma de controle de versão distribuído que oferece diversas funcionalidades aplicadas ao git**.  Podemos hospedar os projetos pessoais. Além disso, quase todos os projetos/frameworks/bibliotecas sobre desenvolvimento open source estão no github, e podemos acompanhá-los através de novas versões, contribuir informando bugs ou até mesmo enviando código e correções. 

## Comandos do Git/GitHub passo a passo:

- CLONAR  

No terminal insira: _**git clone "url"**_ , o projeto é baixado para a sua máquina, e uma pasta com o nome do projeto é criada.

- _**git add "nome do arquivo markdown"**_ 

 No terminal da máquina, insira o git acima. Este comando adiciona o(s) arquivo(s) em um lugar que chamamos de INDEX, que funciona como uma área do git no qual os arquivos possam ser enviados ao Github. É importante saber que ADD não está adicionando um arquivo novo ao repositório, mas sim dizendo que o arquivo (sendo novo ou não) está sendo preparado para entrar na próxima revisão do repositório.

- _**git commit -m "comentário"**_

 No terminal da máquina, insira o git acima. Este comando realiza o que chamamos de “commit”, que significa pegar todos os arquivos que estão naquele lugar INDEX que o comando add adicionou e criar uma revisão com um número e um comentário, que será vista por todos.

 - _**git status**_ 

 No terminal da máquina, insira o git acima. Exibe o status do seu repositório atual

- _**git push -u origin main or master**_

No terminal da máquina, insira o git acima. É usado para publicar todos os seus commits para o github. 
