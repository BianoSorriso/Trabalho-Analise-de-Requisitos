# Trabalho-Analise-de-Requisitos

<p>O Index é um Sistema de Gestão Universitário, que está sendo desenvolvido durante o primeiro semestre de 2025 como parte da nossa equipe na matéria de Análise de Requisitos no curso de Sistemas de Informação pela Unilasalle.</p>
  
<p>O projeto visa a criação de um site composto por 3 portais que são voltados para os adminstradores da faculdade, os professores e os alunos.</p>   

  
### Problema que originou a criação do projeto
  
<p>Foi sugerido pelo professor Anderson Nascimento, que os alunos da matéria de analíse de requisitos criassem um sistema com base em todos os conceitos aplicados em sala de aula (Diagramas de casos de Uso, Técnicas de Elicitação de Requisitos, Histórias de Usuários e etc...)

Pela facilidade conseguir aplicar todos esses conceitos na própria universidade, já que poderiamos aplicar as técnicas de pesquisa, histórias de usuários diretamente com os professores, alunos e com o próprio professor Anderson que é o subcoordenador, foi de decisão conjunta e unânime que o grupo trabalharia na criação de um sistema de gestão universitário.


 Tomada essa decisão, resolvemos criar uma aplicação semelhante ao portal do aluno que usamos na faculdade da empresa TOTVS, onde o aluno pudesse ter acesso a todos os dados vinculados a ele, ou seja: notas de avaliações, faltas, médias gerais, avisos da turma, rematrícula, entre outros.</p>
    
  
## Tecnologias utilizadas
  
<code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/></code> <code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40" /></code>
<code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="40" height="40" /></code>
<code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" width="50" height="50" /></code>
<code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40" height="40" /></code>
<code><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" width="50" height="50" /></code>

  
## Acesso ao Projeto

Para testar o projeto no seu computador, primeiramente você deve realizar o seu download a partir dessa página.
Com o projeto baixado o próximo passo é criar a base de dados do sistema no phpMyAdmin, o comando de criação do BD segue abaixo:

```sh
CREATE DATABASE Index;
```

> Obs: Lembrando que caso você deseje criar o banco de dados pelo Workbench, ou utilizar um nome diferente no BD, só é necessário mudar as pré-definições do aqruivo "Connection.php".

Após a criação do banco de dados é necessário criar também as tabelas, para isso copie o conjunto de código no arquivo database_creation_script.sql e execute-o.

Com as tabelas criadas, é necessário adicionar alguns dados iniciais, para isso, execute os códigos presente no arquivo initial_data_insertion_script.sql

Agora você já pode acessar a aplicação atráves do seu navegador com a url localhost, seguido da porta onde seu servidor web está rodando, no exemplo abaixo como o meu XAMPP estava na porta 8000, a url ficou a seguinte:

```sh
http://localhost:8000
```

O primeiro portal que você deve acessar é o portal do admin, nele você irá configurar a sua universidade. O usuário e o código de acesso para o primeiro acesso estão abaixo:


| Usuário | Código de acesso |
| ------ | ------ |
| Usuário Padrão | 260690 |

Caso você queira saber como funciona cada componente do sistema, EM BREVE criaremos uma documentação do trabalho da nossa equipe. Nele estará toda a explição de cada componente do Sistema Index.
  
  
## Autores
  
Alessandro Davi, Giowanna Azevedo, Isis Ferreira, Ysis Barbosa , Fabiano Bastos.
