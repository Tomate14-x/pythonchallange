# Python Challenge 20200120

### Obrigatório
 
- Trabalhar em um FORK deste repositório em seu usuário;
- O projeto deve utilizar Python
- Documentar todo o processo de investigação para o desenvolvimento da atividade (README.md no seu repositório);


## Estudar o Modelo de Datos

Antes de começar o desafios é imprescindível estudar o modelo [student.txt](./data/student.txt)


## Carregar os arquivos

Nesse ponto teremos que desenvolver um código para ler os dois arquivos:

- Estudantes de Matemática: [student-mat.csv](./data/student-mat.csv)
- Estudantes de Português: [student-por.csv](./data/student-por.csv)


### Mesclar os modelos

Depois de carregar toda a informação, precisaremos trabalhar os dados para fazer análises exploratorias que foi pedido pela equipe de coordenação dos colégios. 

Para conseguir mesclar os dados teremos que usar vários campos já que o sistema que exportou os `.csv` não possui identificadores na base de datos:

```
by=c("school","sex","age","address","famsize","Pstatus","Medu","Fedu","Mjob","Fjob","reason","nursery","internet")
```

Depois de fazer o merge da informação, é necessário imprimir a quantidade de alunos que foram mesclados e os que ficaram de fora por disciplina e colégio.

## Filtrar os dados

1- Os Coodernadores Disciplinares precisam identificar quais alunos tiveram as notas maiores que 10 no primeiro período (G1) em ambas disciplinas e que a mãe seja professora (teacher). 

2- Gerar um relatório de alunos que tiveram notas inferiores a 6 nos dois primeiros períodos, G1 e G2 e que tenha a mãe como professora. 

3- Listar o porcentagem de alunos que tiveram ajuda extra-curricular segmentado por colégios. 

4- Revisar o modelo e adicionar alguma informação que seja relevante aos Coodernadores Disciplinares. 

Para apresentar os dados, gerar os relatórios no Console de execução ou por meio de uma REST API. 


## Readme do Repositório
 
- Deve conter o título de cada projeto
- Uma descrição de uma frase
- Como instalar e usar o projeto (instruções)
- Não esqueça o [.gitignore](https://www.toptal.com/developers/gitignore)
 
## Finalização 

Avisar sobre a finalização e enviar para correção em: [https://coodesh.com/review-challenge](https://coodesh.com/review-challenge) 
Após essa etapa será marcado a apresentação/correção do projeto.

## Instruções para a Apresentação: 

1. Será necessário compartilhar a tela durante a vídeo chamada;
2. Deixe todos os projetos de solução previamente abertos em seu computador antes de iniciar a chamada;
3. Deixe os ambientes configurados e prontos para rodar; 
4. Prepara-se pois você será questionado sobre cada etapa e decisão do Challenge;
5. Prepare uma lista de perguntas, dúvidas, sugestões de melhorias e feedbacks (caso tenha).


## Suporte

Use o nosso canal no slack: http://bit.ly/32CuOMy para tirar dúvidas sobre o processo ou envie um e-mail para contato@coodesh.com. 


