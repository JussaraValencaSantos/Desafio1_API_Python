# 🎸 Desafio 01 — Festival de Música | Python e Análise de Dados

### Generation Brasil | Bootcamp de Análise de Dados — Turma AD05

## 📌 Sobre o projeto

Este projeto faz parte da minha jornada de aprendizado em Análise de Dados, durante o bootcamp da **Generation Brasil — Turma AD05**.

O desafio tem como objetivo aplicar conhecimentos de programação Python na construção e organização de uma base de dados fictícia, simulando o funcionamento de festivais de música.

O tema escolhido foi **Festival de Música**, permitindo explorar informações relacionadas a atrações musicais, gêneros, apresentações, público e vendas de ingressos.

A base será utilizada ao longo dos próximos desafios da formação, envolvendo Estatística, Excel, SQL, Visualização de Dados e Big Data.

## 🎯 Objetivos do projeto

- Aplicar conceitos de programação Python.
- Compreender a estrutura e o relacionamento entre tabelas.
- Trabalhar com dados fictícios de forma organizada.
- Explorar bibliotecas para geração e manipulação de dados.
- Preparar informações para futuras análises de público e faturamento.
- Desenvolver habilidades práticas em Análise de Dados.

## 🎵 Contexto do Festival de Música

O cenário simula uma produtora responsável por organizar festivais de música com duração de três dias.

Cada festival conta com diferentes artistas, gêneros musicais, palcos e modalidades de ingressos.

A proposta é preparar dados que permitam responder futuramente a perguntas como:

- Quais atrações possuem maior público?
- Quais gêneros musicais geram mais faturamento?
- Qual dia apresenta maior volume de vendas?
- Quais modalidades de ingresso geram mais receita?

## 🗂️ Estrutura dos dados

O projeto utiliza duas tabelas relacionadas:

### Tabela 1 — `atracoes`

Tabela de dimensão, responsável por armazenar informações das atrações musicais.

Exemplos de campos:

- `atracao_id` — identificador único da atração.
- `nome_artista_ficticio` — nome do artista ou banda.
- `genero_musical` — gênero musical.
- `edicao_festival` — edição do evento.
- `dia_apresentacao` — data da apresentação.
- `palco` — palco utilizado.

### Tabela 2 — `ingressos_vendidos`

Tabela de fatos, destinada aos registros relacionados às vendas de ingressos.

As duas tabelas são conectadas pelo identificador da atração (`atracao_id`), permitindo relacionar as informações dos artistas aos registros de vendas.

## 🛠️ Tecnologias e ferramentas

| Ferramenta | Utilização no projeto |
|---|---|
| Python | Desenvolvimento da lógica e geração de dados |
| Google Colab | Ambiente de programação |
| Pandas | Organização e manipulação dos dados |
| NumPy | Operações e geração de valores |
| Faker | Criação de dados fictícios |
| Google Sheets | Organização e armazenamento das tabelas |
| GitHub | Documentação e versionamento |

## 📊 Requisitos do desafio

Conforme as orientações do material didático:

- Construir uma base com pelo menos duas tabelas relacionadas.
- Utilizar tabelas de dimensão e fato.
- Trabalhar com dados fictícios.
- Gerar no mínimo 20.000 registros no conjunto de dados.
- Manter a padronização dos nomes das colunas.
- Preparar os dados para as próximas etapas da formação.

O plano de referência do tema Festival de Música prevê aproximadamente **65.100 registros**.

## 🚀 Etapas da formação

| Desafio | Tema |
|---|---|
| 01 | Python, APIs e preparação de dados |
| 02 | Estatística |
| 03 | Excel |
| 04 | SQL e Visualização de Dados |
| 05 | Big Data |

O projeto será atualizado conforme o avanço das atividades.

## 📚 Aprendizados

desenvolvimento dos meus conhecimentos em:

Lógica de programação com Python.

Organização de dados em tabelas.

Relacionamento entre dados.

Geração de informações fictícias.

Utilização de bibliotecas Python.

Preparação de dados para análise.

🔐 Ética e privacidade

Todos os dados utilizados neste projeto são fictícios e destinados exclusivamente a fins educacionais.

📖 Referências

Projeto desenvolvido com base no material disponibilizado pelo professor Rafael durante o bootcamp de Análise de Dados da Generation Brasil.

Material original do desafio

Plano de modelagem — Festival de Música
