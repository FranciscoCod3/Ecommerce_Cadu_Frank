🏖️ E-commerce de Roupas de Praia

Este é um projeto de e-commerce voltado para a venda de roupas de praia (adulto e infantil), desenvolvido com **ASP.NET Core**, **Entity Framework Core** e **SQL Server**. O objetivo é criar uma aplicação completa com recursos de administração, carrinho de compras, checkout, login e integrações externas, utilizando boas práticas como Repository Pattern e Unit of Work.

✨ Funcionalidades

- 📦 Catálogo de produtos com imagens, descrições e preços
- 🛒 Carrinho de compras
- 🧾 Finalização de pedido (checkout)
- 🔍 Filtro por categorias (masculino, feminino, infantil, adulto)
- 🔐 Autenticação e controle de acesso com ASP.NET Identity (em breve)
- 💳 Integração com meios de pagamento (em breve)
- 🚚 Cálculo de frete e integração com transportadoras (em breve)
- 🧾 Emissão de nota fiscal (em breve)
- 👨‍💻 Painel administrativo para gestão de produtos, categorias, pedidos e usuários

🛠️ Tecnologias Utilizadas

- ASP.NET Core 8
- Entity Framework Core
- ASP.NET Identity
- SQL Server
- HTML5, CSS3, JavaScript
- Bootstrap ou Tailwind CSS
- Repository Pattern + Unit of Work

## 📁 Estrutura do Projeto

Ecommerce/
│
├── Areas/
│ └── Admin/
│ ├── Controllers/
│ ├── Views/
│ ├── Models/
│ ├── _ViewImports.cshtml
│ └── _ViewStart.cshtml
│
├── Controllers/
│ ├── HomeController.cs
│ ├── ProdutoController.cs
│ ├── CarrinhoController.cs
│ ├── CheckoutController.cs
│ ├── PedidoController.cs
│ └── AccountController.cs
│
├── Models/
│ ├── Produto.cs
│ ├── Categoria.cs
│ ├── ItemCarrinho.cs
│ ├── Pedido.cs
│ ├── Cliente.cs
│ ├── Endereco.cs
│ ├── Usuario.cs
│ └── Pagamento.cs
│
├── Data/
│ ├── ApplicationDbContext.cs
│ ├── SeedData.cs
│ ├── Migrations/
│ └── UnitOfWork/
│
├── Repositories/
│ ├── Interfaces/
│ └── Implementations/
│
├── Services/
│ ├── Interfaces/
│ ├── PagamentoService.cs
│ ├── NotaFiscalService.cs
│ ├── TransportadoraService.cs
│ ├── EmailService.cs
│ ├── EstoqueService.cs
│ └── LoggerService.cs
│
├── ViewModels/
│ ├── ProdutoViewModel.cs
│ ├── CarrinhoViewModel.cs
│ ├── CheckoutViewModel.cs
│ ├── PedidoViewModel.cs
│ ├── LoginViewModel.cs
│ ├── RegisterViewModel.cs
│ └── EnderecoViewModel.cs
│
├── Helpers/
│ ├── ImagemHelper.cs
│ ├── RoleHelper.cs
│ └── ValidadorDocumentoHelper.cs
│
├── Views/
│ ├── Shared/
│ ├── Home/
│ ├── Produto/
│ ├── Carrinho/
│ ├── Checkout/
│ └── Account/
│
├── wwwroot/
│ ├── css/
│ ├── js/
│ ├── images/
│ └── lib/
│
├── appsettings.json
├── Program.cs
├── Startup.cs
└── README.md

## 🚧 Status do Projeto

> 🔨 **Em desenvolvimento** — funcionalidades principais estão sendo implementadas. Login, pagamento e emissão de nota fiscal serão adicionados nas próximas etapas.

## 📌 Objetivo

Criar uma aplicação realista de e-commerce com foco em:

- Estrutura modular e escalável
- Separação clara entre camadas (MVC)
- Boas práticas de codificação e arquitetura
- Integração com serviços externos (pagamento, frete, nota fiscal)

## 📷 Capturas de Tela

> Em breve

## 📄 Licença

Distribuído sob a licença [MIT](LICENSE).

## 🤝 Contribuindo

Pull requests são bem-vindos. Para sugestões maiores, abra uma issue para discutirmos suas ideias.

---
Feito Por Cadu e Francisco




