# Termometro de Marcas 🌡️ - Projeto de Sistemas

## Equipe <br>
Matheus: add email<br>
Arthur Delpupo Coelho: arthurdelpupocoelho40@gmail.com<br>
Thiago Dutra Nascimento: thiagoduna0@gmail.com<br>
Manoel: manoel.rl@gmail.com<br>
Lorran Gabriel: lorrangabriel20@gmail.com<br>

## Sumário

- [1.Minimundo](#1-Minimundo)<br>
- [2.Requisitos](#2-Requisitos)<br>
- [3.Casos de uso](#3-Casos-de-uso)<br>
- [4.Descrição dos Casos de Uso](#4-Descrição-dos-Casos-de-Uso)<br>
- [5.Modelo de Classes](#5-Modelo-de-Classes)<br>

### 1. Minimundo
> O projeto “Termômetro de Marcas” é uma plataforma cujo objetivo é informar aos usuários, de forma qualitativa, sobre determinado produto ou marca, no qual o usuário irá inserir as palavras chaves que deseja filtrar e a plataforma se responsabilizará por gerar relatórios sobre o tema filtrado. Dessa forma, é esperado desenvolver um sistema que receba palavras chaves e, através de operações internas, retorne uma análise qualitativa sobre o tema proposto.
<br>O sistema realiza a filtragem das marcas através do twitter, no qual ele identifica todos os tweets que citam esta e avalia qualitativamente o tweet, armazenando a avaliação, data do tweet e indicadores como likes, retweets, comentários, visualizações e os autores dos principais tweets sobre o tema.
<br>O sistema possui usuários, sobre eles, deseja-se armazenar seus dados pessoais, como CPF, nome, data de nascimento, e-mail e endereço. Através do cadastro dos usuários, eles podem fazer uma busca direta sobre uma determinada marca, ou selecioná-la dentre as categorias disponíveis. Ao selecionar um produto ou marca o usuário tem a possibilidade de filtrar os resultados, levando em consideração a data, localização, relevância, frequência, qualidade e repercussão.
<br>Dessa forma, o sistema deve ser capaz de gerar e apresentar ao usuário relatórios que levam em consideração todos os dados supracitados, com base no que ele pesquisou e filtrou. O termômetro de marcas deve proporcionar a possibilidade de salvar o relatório gerado.


### 2. Requisitos
  #### 2.1 RF
  
Identificador | Descrição | Prioridade | Dependencia
:---------: | ---------- | :---------: | :---------: |
RF01 | O sistema deve permitir o cadastro de usuarios.       |Alta|  |
RF02 | O sistema deve permitir o cadastro de marcas.       |Alta|  |
RF03 | O sistema deve ser capaz de acessar a API publica do twitter para obter os dado.       |Alta|  |
RF04 | O sistema deve realizar .       |Alta|  |

  #### 2.2 RN
Identificador | Descrição | Prioridade | Dependencia 
:---------: | ---------- | :---------: | :---------: |
RN01 | Para verificar os trends de uma marca a mesma deve estar cadastrada        |Alta|  |

  #### 2.3 RNF
Identificador | Descrição | Categoria | Escopo | Prioridade | Dependencia
:---------: | ---------- | :---------: | :---------: | :---------: | :---------: |
RNF01 |O sistema deve possuir uma linguagem simples e ser de facil navegabilidade.        |Usabilidade| Sistema|Alta|  |
RNF02 |O sistema deve ser capaz de autenticar usuários.                                   |Segurança de acesso |Sistema|
RNF03 |O sistema deve ser capaz de futuramente possuir uma versão mobile.                 |Portabilidade|Funcionalidade|
RNF04 |O sistema deve ser capaz de receber mensagens e sugestões de qualquer visitante que seja uma pessoa fisica.           |Usabilidade|Sistema|
RNF05 |A persistência das informações deverão ser implementadas em um primeiro momento utilizando TAL TECNOLOGIA (armazenamento na nuvem). Entretanto no futuro deve ser possível utilizar outras tecnologias de persistência.| Portabilidade | Sistema  |
RNF06 |As funcionalidades dos administradores deverão ser acessiveis apenas via plataforma desktop, já os usuários cadastrados poderão ter acesso a suas funcionalidades tanto na versão mobile quanto na versão desktop.| Funcionalidade | Sistema |
RNF07 | Um usuário novato/visitante deverá aprender qualquer funcionalidade em no máximo 5 minutos, visto que a maioria das funcionalidades serão de visualização e pesquisa.|    Facilidade de Operação   |   Funcionalidade    |
RNF08 | A entrada de dados/preenchimento dos campos deve durar no máximo 1 minuto, para usuários experientes e que já estão cadastrados na plataforma.|   Operacionalidade    |   Funcionalidade   | 

### 3. Casos de uso

Adicionar IMAGEM

### 4. Descrição dos Casos de Uso

Projeto: Tibico - Sistema de Registro Acadêmico Subsistema: ControleInterno
Caso de Uso: Controlar Turma

Descrição Sucinta: Parte deste caso de uso já foi descrito anteriormente na tabela de casos de uso cadastrais. Ele é responsável por iniciar e finalizar turma, alocar professor, iniciar e finalizar período de matrícula.

Nome do Fluxo de Eventos Normal | Precondição | Descrição 
:---------: | ---------- | ---------- |
Alocar Professor | 1- Possuir Turma cadastrada. | 1 – O funcionário seleciona uma turma.<br> 2 – O sistema exibe os professores disponíveis de horário e que a área da disciplina seja igual a área de atuação do professor.<br>3 – O funcionário seleciona o professor.<br>4 – O professor é alocado na turma.


### 5. Modelo de Classes

Adicionar IMAGEM
