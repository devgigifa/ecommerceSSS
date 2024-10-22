
# Starry Sky Shop - e-commerce

Um simples projeto de e-commerce desenvolvido em HTML, CSS e JavaScript. Permite que os usuários criem contas, adicionem produtos, façam login, visualizem produtos e realizem compras.

## Estrutura do Projeto

- `index.html`: Página inicial do e-commerce.
- `atualizacao.html`: Área do administrador para adicionar novos produtos.
- `produto.html`: Página de detalhes do produto.
- `script.js`: Lógica do aplicativo.
- `style.css`: Estilos da aplicação.
- `imagens/`: Diretório para as imagens dos produtos.

## Funcionalidades

### 1. Cadastro e Login de Usuários

- Os usuários podem criar uma conta através de um prompt que solicita nome de usuário e senha.
- Os usuários podem fazer login para acessar as funcionalidades da loja.

### 2. Visualização de Produtos

- Os produtos são carregados a partir do `localStorage`.
- Cada produto exibe seu nome, preço e um botão para compra que redireciona para o link do produto na Amazon.

### 3. Carrinho de Compras

- O usuário pode adicionar produtos ao carrinho e visualizar o total da compra.
- Um alerta é exibido com os detalhes da compra e a opção de confirmar ou cancelar a transação.

### 4. Administração de Produtos

- A área de administração permite a inserção de novos produtos, incluindo nome, código, preço, link e descrição.

## Como Usar

1. Abra o `index.html` em um navegador.
2. Crie uma conta usando o botão "Crie seu login".
3. Faça login para acessar a loja.
4. Navegue pelos produtos disponíveis e adicione-os ao carrinho.
5. Clique no carrinho para visualizar e finalizar a compra.

## Estrutura do Código

### HTML

O código HTML é estruturado em três páginas principais: `index.html`, `atualizacao.html` e `produto.html`, cada uma com cabeçalho, corpo e rodapé.

### JavaScript

O arquivo `script.js` contém as seguintes principais funções:

- `getDados()`: Salva os dados do produto no `localStorage`.
- `montaHTML()`: Monta os cards dos produtos na página inicial.
- `criaLogin()`: Cria uma nova conta de usuário.
- `abreTelaLogin()`: Permite que o usuário faça login.
- `compra()`: Adiciona um produto ao carrinho.
- `calculaCesta()`: Calcula o total da compra e exibe os detalhes.
- `carregaProduto()`: Carrega os detalhes do produto na página de produto.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript

## Conclusão

O projeto Starry Sky Shop é uma demonstração de um e-commerce básico que utiliza `localStorage` para gerenciamento de dados. É uma boa base para expandir e adicionar mais funcionalidades, como integração com APIs, gerenciamento de estoque e uma interface mais rica.
