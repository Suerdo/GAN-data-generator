# Projeto de Geração de Dados Fictícios com Consistência

## Descrição

Este projeto visa a criação de dados fictícios realistas, consistentes e coerentes, utilizando a biblioteca Faker para gerar dados como nome, e-mail, CPF, RG, entre outros. O objetivo é criar um conjunto de dados sintéticos que possam ser utilizados em treinamentos, testes e simulações, enquanto garantem que os campos gerados (como nome, e-mail e CPF) sejam consistentes entre si.

## Funcionalidades

- **Geração de Dados Fictícios**: O projeto gera dados como nome, e-mail, CPF, telefone, RG, CNH, tipo sanguíneo, endereço, login e senha, utilizando a biblioteca Faker.
- **Consistência entre Campos**: O nome e o e-mail são gerados de maneira consistente, garantindo que o e-mail esteja alinhado com o nome gerado.
- **Gerador de CPF**: O CPF é gerado de maneira realista, seguindo o formato típico dos CPFs brasileiros.
- **Exportação para Excel**: Os dados gerados são exportados para um arquivo Excel para fácil visualização e uso.

## Tecnologias Utilizadas

- **Python**: A linguagem de programação utilizada para o desenvolvimento do projeto.
- **Faker**: Biblioteca para geração de dados fictícios realistas.
- **TensorFlow/Keras**: Para construção de modelos de rede adversarial generativa (GAN) (se necessário, para campos adicionais além de nome, e-mail e CPF).
- **Pandas**: Para manipulação de dados e exportação para Excel.
- **NumPy**: Para operações numéricas e manipulação de arrays.

