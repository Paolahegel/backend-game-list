# Projeto Backend Lista de Jogos
# Sobre o Projeto
Este projeto foi desenvolvido durante a participação na semana Intensivão Java Spring organizado pelo [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").
A proposta é disponibilizar uma API que fornece a lógica e regras de negócio para um front-end (ainda não desenvolvido) com integração ao banco de dados. Consiste em um sistema de jogos onde é possível organizar a lista de jogos conforme requisição.

## Funcionalidades
- **Busca completa de jogos:** Obtém a lista de jogos com descrições completas.
- **Busca breve de jogos:** Obtém a lista de jogos com descrições curtas.
- **Busca por ID:** Obtém a lista com o ID e nome do jogo.
- **Atualização de posição:** Atualiza no banco de dados a posição dos jogos na lista.

## Modelo Conceitual
![Modelo de domínio DSList](https://raw.githubusercontent.com/devsuperior/java-spring-dslist/main/resources/dslist-model.png)

## Tecnologias Utilizadas
- **Linguagem de Programação:** Java 21
- **Framework:** Spring Boot
- **Banco de Dados:** H2 Console
- **Ferramentas de Teste:** PostMan
- **Gerenciamento de Build e Dependências**: Maven
- **Controle de Versão:** Git/GitHub

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto_final_bloco_02.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd projeto_final_bloco_02
   ```

3. Configure o banco de dados no arquivo `application.properties`.

4. Execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

5. Utilize o PostMan ou outra ferramenta de teste para acessar os endpoints.
