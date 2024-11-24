# Gerenciador de Lojas e Produtos

## Descrição
Este projeto consiste em uma aplicação para gerenciar lojas e produtos, implementando diferentes tipos de lojas com características específicas. Foi desenvolvido para um desafio da faculdade na disciplina de Programação.

## Funcionalidades
- **Alimentação**: Representa lojas do ramo alimentício e armazena a data do alvará de funcionamento.
- **Bijuteria**: Armazena a meta de vendas da loja de bijuterias.
- **Cosmético**: Representa lojas de cosméticos e armazena a taxa de comercialização.
- **Informatica**: Armazena o valor do seguro dos eletrônicos vendidos na loja.
- **Vestuario**: Indica se a loja de vestuário vende produtos importados.
- **Produto**: Representa os produtos vendidos nas lojas, incluindo nome, preço e data de validade.
- **Loja**: Superclasse que gerencia produtos no estoque.
- **Shopping**: Gerencia um conjunto de lojas, permitindo inserir e remover lojas, além de calcular a quantidade de lojas por tipo e a loja de informática com o seguro mais caro.

## Estrutura do Projeto
O projeto está organizado nas seguintes classes:

- `Alimentacao`
- `Bijuteria`
- `Cosmetico`
- `Data`
- `Endereco`
- `Informatica`
- `Loja`
- `Produto`
- `Shopping`
- `Vestuario`
- `Principal`

## Pré-requisitos
- Java Development Kit (JDK) 8 ou superior
- IDE Java (Eclipse, IntelliJ, BlueJ, etc.)

## Como Compilar e Executar

### Compilar
1. Abra seu terminal ou prompt de comando.
2. Navegue até o diretório do projeto.
3. Compile os arquivos `.java` utilizando o comando:
   ```sh
   javac Etapa4/*.java
