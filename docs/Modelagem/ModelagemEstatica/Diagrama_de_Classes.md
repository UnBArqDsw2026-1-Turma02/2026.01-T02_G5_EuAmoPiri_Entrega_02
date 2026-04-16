# 2.1.2 Diagrama de Classes

## Introdução

Um Diagrama de Classes é um dos principais artefatos da UML, utilizado na modelagem de sistemas orientados a objetos para representar a estrutura estática de uma aplicação.

Ele tem como objetivo descrever, de forma visual, como o sistema foi modelado, apresentando as classes, seus atributos, seus métodos e os relacionamentos existentes entre elas. Dessa forma, o diagrama permite compreender como as entidades do domínio estão organizadas e como interagem entre si.

Dentro do contexto de modelagem, o diagrama de classes é essencial para transformar requisitos do mundo real em uma representação estruturada, servindo como base para o projeto e implementação do sistema.

Os principais relacionamentos utilizados na modelagem são:

- **Associação**: representa uma relação estrutural entre classes, indicando que objetos de uma classe se conectam a objetos de outra. Pode incluir **multiplicidade**, definindo quantas instâncias participam da relação.

- **Herança**: define uma relação hierárquica onde uma classe filha herda atributos e métodos de uma classe pai, promovendo reutilização e especialização na modelagem.

- **Agregação**: representa uma relação de “todo-parte” mais fraca, onde as partes podem existir independentemente do todo. É usada quando há composição lógica, mas sem dependência de ciclo de vida.

- **Composição**: é uma forma mais forte de agregação, onde as partes dependem totalmente do todo para existir. Nesse caso, há dependência de ciclo de vida entre os objetos.

- **Dependência**: indica que uma classe utiliza outra de forma temporária, geralmente como parâmetro de método ou variável local, sem manter uma relação estrutural permanente.

## Objetivo

O diagrama de classes tem como objetivo apoiar a modelagem estrutural do sistema, representando de forma clara e organizada as classes, seus atributos, métodos e os relacionamentos entre elas. Essa modelagem busca transformar os requisitos do domínio em uma estrutura orientada a objetos, servindo como base para o desenvolvimento da aplicação.

| Data       | Versão | Descrição                                                      | Autor                                                       | Revisores |
| ---------- | ------ | -------------------------------------------------------------- | ----------------------------------------------------------- | --------- |
| 15/04/2026 | `1.0`  | Criação inicial do documento e elaboração dos tópicos iniciais | [Eduardo Ribeiro](https://github.com/EduardoRibeiroXavier) |
