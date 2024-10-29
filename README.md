# Projeto-Banco-de-Dados
Desenvolvimento de Aplicações com Banco de Dados - Trabalho Prático 3° Bimestre 

## 1. Introdução

O projeto tem como objetivo o desenvolvimento de uma loja de livros, uma plataforma online que facilite o acesso, organização e compartilhamento de livros digitais e físicos. O site permitirá que 
os usuários visualizem, pesquisem e baixem uma gama de livros digitais em diferentes categorias, proporcionando uma experiencia personalizável e acessível de acordo com o gosto pessoal do leitor. 
Além disso o projeto contará com controle de estoque sob as compras feitas online, integrando um banco de dados ao site, informando ao cliente a quantidade exata de cópias disponíveis daquele produto e encerrando a possibilidade de compra ao encerrar o estoque.  

## 2. Requisitos do Sistema
### Requisitos funcionais:
Registro de Usuários - Uma das funcionalidades será o registro de cada usuário para o login no site, registrando e-mail (ou telefone) e senha no banco de dados, onde será feita a comunicação entre site e o dba.  

### Formulário 
Na mesma página de login será feita a inserção de um breve formulário sobre os interesses e preferencias do usuário, permitindo assim que seja feita recomendações de livros populares e recém-lançados, tudo isso com base nas informações disponibilizadas pelo usuário. 

### Filtro de Busca 
O sistema de filtro de busca será desenvolvido com base nas opções seguintes opções:

- Tema;
- Autor;
- Preço.

Tornando assim a experiencia do usuário mais prática e ágil, aumentando a probabilidade de que o usuário encontre livros de sua preferência.

### Controle de Estoque 
O controle de estoque trará o seguinte funcionamento:

--> O “sistema” registra e monitora em tempo real a quantidade de cada produto no banco de dados, atualizando automaticamente a disponibilidade conforme as vendas ocorrem.

--> Quando um produto se esgota, o sistema reconhece essa alteração, e exibe a quantidade disponível como "Esgotado". 

Esse sistema além de informar a quantidade de produtos disponível, impede que os clientes tentem adquirir produtos fora de estoque, indisponibilizando a compra de determinado produto.

### Requisitos não funcionais:

### Segurança 
Uso do protocolo HTTPS para garantir que a comunicação entre o cliente e o servidor seja segura.

### Desempenho 
A otimização do desempenho será feita através do uso de imagens de tamanho apropriado, evitando que a página demore para carregar. E também a organização devida em todo código do projeto, a fim de gerar um ambiente livre de erros e de alta resposta.  

### Escalabilidade:
Pensando na escalabilidade, o sistema da loja será projeto para que mudanças em seu código sejam fáceis e descomplicadas, um código de fácil implementação de novos recursos, tendo em vista que novas opurtunidades de expansão são constantes em uma loja online.

## 3. Modelagem do Banco de Dados

![Captura de tela 2024-10-29 162807](https://github.com/user-attachments/assets/21397fd3-c2cf-43c3-b848-ce080aec6b97)

## 4. Arquitetura da Aplicação

### Tecnologias Utilizadas: 

### Front End.
Linguagens usadas: 

HTML;

CSS;

Java Script. 

#### Frameworks:

Flask;

Tailwind.

### Back End.
Linguagens usadas: 

Python;

Java Script;

SQL.  

#### Frameworks:

Flask.

## 5. Design da Interface do Usuário

### Base para criação dos recursos visuais do site

![img_kindleWeb_BR2x _CB610886625_](https://github.com/user-attachments/assets/fa2b734a-8cee-40a6-aa21-91a081677b16)
