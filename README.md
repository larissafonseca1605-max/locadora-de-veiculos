# Locadora de Veículos

Projeto prático desenvolvido em Java para simular o funcionamento de uma locadora de veículos.

## Objetivo

O sistema permite consultar valores de aluguel, alugar e devolver veículos, aplicando conceitos de Programação Orientada a Objetos.

## Tecnologias utilizadas

- Java 21
- IntelliJ IDEA

## Estrutura do projeto

- **Tarifavel.java:** interface que define o método de cálculo do aluguel.
- **Veiculo.java:** classe abstrata com os atributos e comportamentos comuns dos veículos.
- **Carro.java:** classe que representa carros e implementa o cálculo do aluguel com taxa de limpeza de R$ 20,00.
- **Moto.java:** classe que representa motos e implementa o cálculo do aluguel com taxa de limpeza de R$ 5,00.
- **Main.java:** classe principal responsável pela execução e pelos testes.

## Conceitos de POO aplicados

- Encapsulamento
- Herança
- Polimorfismo
- Classe abstrata
- Interface

## Execução

Para executar o projeto, basta abrir no IntelliJ IDEA e rodar a classe `Main.java`.

O programa realiza testes de consulta de valores, aluguel, devolução e alteração de diárias.
