# WingtipToys – ASP.NET 4.5 Web Forms Sample

Este repositório contém uma implementação prática dos tutoriais oficiais da Microsoft para **ASP.NET Web Forms 4.5**, utilizando o projeto de exemplo **WingtipToys**.  
O WingtipToys é uma aplicação fictícia de comércio eletrônico que demonstra os principais recursos do **ASP.NET Web Forms** e do **Entity Framework 6**, servindo como referência para aprendizado e estudo.

---

## 📌 Objetivos do Projeto
- Demonstrar a criação de uma aplicação ASP.NET Web Forms do zero  
- Implementar **camada de acesso a dados (DAL)** com Entity Framework Code First  
- Utilizar **páginas mestras (Master Pages)** para layout consistente  
- Explorar **controles de servidor** e **validação**  
- Configurar **roteamento amigável** e **bundling/minification** para otimização  
- Implementar **autenticação e autorização** com ASP.NET Membership  
- Popular o banco de dados com dados iniciais usando **Database Initializer**

---

## 📂 Estrutura
- **Models/** → Classes de domínio (`Product`, `Category`) e contexto (`ProductContext`)  
- **DAL/** → Inicializadores e lógica de acesso a dados  
- **Pages/** → Páginas Web Forms (`.aspx`) com exemplos de catálogo, carrinho e checkout  
- **App_Start/** → Configuração de rotas e bundles  
- **Web.config** → Configuração da aplicação e connection string  

---

## 🚀 Como executar
1. Abra o projeto no **Visual Studio** (2017 ou superior)  
2. Certifique-se de ter o **SQL Server LocalDB** instalado  
3. Ajuste a connection string `WingtipToys` no `Web.config` se necessário  
4. Pressione **F5** para compilar e executar  
5. A aplicação será carregada no navegador, simulando uma loja online de brinquedos  

---

## 📖
