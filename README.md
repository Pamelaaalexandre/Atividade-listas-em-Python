
🛍️ Sistema de Cadastro de Produtos (Python CLI)

Este é um projeto simples e prático desenvolvido em Python para consolidar conceitos essenciais de programação, como estruturas de dados (listas), estruturas condicionais, laços de repetição (loops) e manipulação dinâmica de dados.

O projeto simula um sistema básico de gerenciamento de estoque, dividido em blocos de atividades.

🚀 Funcionalidades
O sistema está estruturado em 4 Blocos de Atividades:

Bloco 1 (Inicialização): Define o estoque inicial de produtos e seus respectivos preços, exibindo a lista formatada na tela.
Bloco 2 (Cadastro): Permite ao usuário cadastrar dinamicamente novos produtos informando o nome e o preço via teclado.
Bloco 3 (Remoção segura): Realiza a remoção controlada de itens do estoque (utilizando o método .pop()), garantindo que o programa não quebre caso o estoque já esteja vazio.
Bloco 4 (Visualização Avançada): Área reservada para novas implementações e consolidação do painel de controle do estoque.
🛠️ Tecnologias Utilizadas
Python 3.x
Google Colab (para desenvolvimento interativo)
💻 Como Executar o Projeto
Você pode rodar este projeto em qualquer ambiente Python ou diretamente no Google Colab seguindo os passos abaixo:

Abra o arquivo do notebook (.ipynb).
Execute o Bloco 1 para criar a base do estoque.
Execute o Bloco 2 para adicionar novos itens interagindo com o console.
Execute o Bloco 3 para remover o último item adicionado com segurança.
📄 Demonstração de Código
Estrutura Base de Dados
# Inicializando listas de produtos e preços
produtos = ["Camiseta Basica", "Calça Jeans", "Jaqueta Corta-Vento"]
precos = [49.90, 129.90, 219.90]

# Exibição elegante utilizando zip
for produto, preco in zip(produtos, precos):
    print(f"O produto {produto} custa R${preco:.2f}")
🤝 Contribuindo
Contribuições são super bem-vindas! Sinta-se à vontade para abrir uma Issue ou enviar um Pull Request:

Faça um Fork do projeto.
Crie uma nova branch para sua funcionalidade (git checkout -b feature/NovaFuncionalidade).
Salve suas alterações (git commit -m 'Adiciona nova funcionalidade').
Envie para o seu repositório original (git push origin feature/NovaFuncionalidade).
Abra um Pull Request.
💡 Desenvolvido para fins de aprendizado de lógica de programação com Python!
