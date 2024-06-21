# Desenvolvimento de API RESTful com ASP.NET 8 🚀

### Background

Este projeto visa criar uma API RESTful utilizando ASP.NET 8 para gerenciar uma entidade de exemplo (como "Produto") 🛒, conectando-se a um banco de dados PostgreSQL usando Entity Framework. Além disso, a API consumirá o serviço Fixer.io para realizar conversões de moedas 💱.

### Funcionais
- Deve ser possível criar, ler, atualizar e deletar registros de "Produto" no banco de dados PostgreSQL 🗄️.
- A API deve consumir a API Fixer.io para conversão de moedas 🌍.
- Deve ser possível listar produtos com seus preços convertidos para diferentes moedas 💲.

### Não Funcionais
- Deve ser desenvolvida em ASP.NET 8 💻.
- A conexão com o banco de dados deve ser feita utilizando Entity Framework 🔗.
- Devem ser implementados testes unitários com xUnit 🧪.
- A segurança e boas práticas de desenvolvimento de APIs RESTful devem ser seguidas 🔒.
- Deve ser criado dockerfile/docker compose 🐳.
- Deve ser publicada no Azure ☁️.

### Consumo da API Fixer

A API Fixer será utilizada para obter taxas de câmbio e realizar conversões de moedas. Isso será feito através de chamadas HTTP a endpoints específicos da API Fixer. [Link](https://fixer.io/)

## Entregas 📦

Avaliação da implementação e performance da API:
- Verificar se todas as funcionalidades CRUD estão operacionais ✅.
- Testar a integração com a API Fixer 🔄.
- Validar a precisão das conversões de moeda 💹.
- Avaliar a performance e segurança da API em ambiente de produção 🔍.
- O projeto deve ser entregue em um repositorio do github privado e enviado para o e-mail: github@consys.tec.br