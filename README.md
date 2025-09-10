# Tabela FIPE

O **Tabela FIPE** é uma aplicação desenvolvida em **Java** utilizando **Spring Boot**, que permite consultar os preços médios de veículos no Brasil com base na **Tabela FIPE**. O projeto utiliza recursos modernos de Java, como **lambdas e streams**, e faz **serialização e deserialização de dados** com a biblioteca **Jackson**, garantindo manipulação eficiente de coleções e dados JSON.  

## 🛠️ Tecnologias Utilizadas

- **Java 24** – aproveitando funcionalidades do Java 8, como lambdas e streams, para maior eficiência e clareza no código.  
- **Spring Boot** – framework utilizado para simplificar o desenvolvimento e gerenciamento da aplicação.  
- **Jackson** – biblioteca responsável por serializar e desserializar os objetos Java em JSON e vice-versa.  
- **Maven** – para gerenciamento de dependências e build do projeto.  

## ⚙️ Funcionalidades

O programa realiza consultas detalhadas de **carros, motos e caminhões**, seguindo o fluxo abaixo:

1. O usuário escolhe o tipo de veículo (**carro**, **moto** ou **caminhão**).  
2. O programa apresenta as marcas disponíveis para o tipo escolhido e solicita que o usuário informe o **código da marca**.  
3. Em seguida, são exibidos os **modelos** disponíveis da marca escolhida e o usuário deve informar um **trecho do nome do veículo** que deseja buscar.  
4. O programa apresenta os modelos que correspondem ao trecho informado.  
5. Por fim, o usuário informa o **código do modelo** desejado para consultar a avaliação e o preço médio do veículo de acordo com a Tabela FIPE.  

Outras funcionalidades incluem:  

- Listar todas as marcas e modelos disponíveis na Tabela FIPE.  
- Processamento eficiente de dados utilizando **streams** e **lambdas**, tornando o código mais limpo e performático.  
- Manipulação de dados em **JSON**, permitindo fácil integração com outras aplicações ou APIs.  

## 🌐 API Utilizada

O projeto consome dados da API pública da Tabela FIPE disponibilizada pelo site [FIPE API HTTP REST](https://deividfortuna.github.io/fipe/?ref=public_apis&utm_medium=website), que fornece informações atualizadas sobre veículos, marcas, modelos e preços médios.  
