# trabalho do senai - estrutura de dados

# Trabalho da UC "Estrutura de dados" do curso de Desenvolvimento de Sistemas do Ensino Tecnico SENAI/SESI, realizada no ano de 2025 e começada dia 02/06

![Divisão](https://img.shields.io/badge/Firjan-Senai/Sesi-orange?style=for-the-badge&labelColor=blue)

Nosso sistema de e-commerce marketplace foi idealizado com o propósito de reunir, em uma única plataforma digital, diversas empresas fictícias especializadas na comercialização de produtos voltados ao mercado petshop. A proposta é criar um ambiente colaborativo e competitivo onde diferentes vendedores possam divulgar seus produtos, atrair consumidores e realizar vendas de forma simplificada e eficiente. O sistema oferece uma experiência integrada para o usuário, combinando funcionalidades de navegação, seleção de itens, gerenciamento de pedidos e finalização de compras, tudo em uma interface amigável e funcional. Além disso, a estrutura técnica foi planejada com foco na organização e no desempenho, utilizando diferentes tipos de dados para otimizar cada etapa da jornada de compra e garantir segurança, agilidade e escalabilidade à plataforma.

contamos com: 

🔐 Sistema de Login e Logout
Utiliza uma estrutura de matriz, armazenando múltiplos usuários e suas credenciais em linhas e colunas. Essa organização facilita a verificação de acesso, controle de sessões e o gerenciamento eficiente das autenticações.

📦 Lista de Produtos
Implementada com uma estrutura do tipo set, garantindo que os produtos cadastrados não se repitam. Isso evita duplicações no catálogo e melhora a performance em buscas e filtragens.

🛒 Carrinho de Compras
Baseado em dicionários (dict), permitindo relacionar cada produto selecionado com suas quantidades, preços e outras informações relevantes. Essa estrutura torna o acesso e a atualização dos itens do carrinho rápidos e precisos.

💳 Área de Pagamento
Utiliza um vetor (array) para armazenar as etapas e opções do pagamento (como forma de pagamento, parcelas, status, etc.), garantindo um fluxo linear e eficiente até a conclusão da compra.

👤 Dados do Usuário
Estão diretamente integrados ao sistema de login. Após a autenticação, as informações do usuário (como nome, endereço, histórico de compras e preferências) são carregadas e mantidas acessíveis durante a navegação, permitindo uma experiência personalizada e segura.
