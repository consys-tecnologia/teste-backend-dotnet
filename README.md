# Desafio Técnico: Desenvolvimento de API RESTful com ASP.NET 8 🚀

## Background

O objetivo deste desafio é criar uma API RESTful utilizando ASP.NET 8 para gerenciar uma entidade de exemplo, como "Produto" 🛒, conectando-se a um banco de dados PostgreSQL usando Entity Framework. A API também consumirá o serviço Fixer.io para realizar conversões de moedas 💱. Espera-se que o desenvolvimento siga boas práticas de engenharia de software, incluindo SOLID, Clean Code, TDD, Clean Architecture e DDD.

### Requisitos Funcionais
1. **CRUD de Produtos**: Implementar as operações de criação, leitura, atualização e deleção de produtos no banco de dados PostgreSQL 🗄️.
2. **Integração com API Externa**: Consumir a API Fixer.io para obter taxas de câmbio e realizar a conversão de preços de produtos para diferentes moedas 💲.
3. **Listagem de Produtos com Conversão de Moeda**: Deve ser possível listar os produtos com seus preços convertidos para uma ou mais moedas com base nas taxas da API Fixer.
4. **Paginação e Filtros**: Implementar paginação e filtros nos endpoints de listagem de produtos.

### Requisitos Não Funcionais
1. **Arquitetura Limpa (Clean Architecture)**: O projeto deve seguir os princípios da Clean Architecture, separando camadas de domínio, aplicação, infraestrutura e interfaces de forma clara.
2. **Design Orientado a Domínio (DDD)**: O domínio deve ser modelado seguindo os conceitos de DDD, com agregados, entidades e repositórios devidamente definidos.
3. **Boas Práticas de SOLID**: O código deve respeitar os princípios SOLID, com separação de responsabilidades, uso adequado de injeção de dependências e padrões de design apropriados.
4. **Testes Unitários e Testes de Integração (TDD)**: A aplicação deve ser construída com a abordagem de TDD, utilizando xUnit para cobrir as funcionalidades principais e integração com a API externa.
5. **Segurança e Boas Práticas REST**: A API deve seguir boas práticas de segurança, como autenticação/autorização (OAuth2 ou JWT), versionamento de API e tratamento adequado de erros.
6. **Monitoramento e Observabilidade**: Implementar logging, monitoramento e rastreamento (Tracing) usando ferramentas como Serilog e OpenTelemetry.
7. **Containerização**: Deve ser criado um `Dockerfile` e `docker-compose` para facilitar a configuração e execução da aplicação, com suporte a múltiplos ambientes (dev, staging, produção).
8. **CI/CD**: Implementar um pipeline de CI/CD usando GitHub Actions ou outra ferramenta, com build, testes e deploy automatizado no **provedor de nuvem de sua escolha** (AWS, Azure, Google Cloud, etc.).
9. **Publicação em Cloud**: A API deve ser publicada em um ambiente de produção no **provedor de nuvem de sua escolha**.

### Consumo da API Fixer
- A API Fixer será utilizada para obter taxas de câmbio e realizar as conversões de moeda. A implementação deve ser desacoplada, utilizando o padrão *Service* ou *Adapter* para integração com serviços externos, permitindo facilidade de substituição ou expansão.

### Entregáveis 📦
1. **Código Fonte**: O projeto deve ser entregue em um repositório privado no GitHub, com um `README.md` detalhando a arquitetura, decisões técnicas, instruções de execução e endpoints da API.
2. **Testes**: Incluir cobertura de testes unitários e de integração para o CRUD de produtos e integração com a API Fixer.
3. **Pipeline CI/CD**: Pipeline configurado no GitHub Actions (ou ferramenta similar) com etapas de build, testes e deploy.
4. **Ambiente em Produção**: A API deve estar publicada em um ambiente de produção no **provedor de nuvem de sua escolha**, com logs e monitoramento configurados.
5. **Documentação da API**: Usar Swagger para documentar os endpoints da API.
6. **Desempenho e Segurança**: Realizar otimizações de desempenho (cache, consultas otimizadas) e garantir segurança (autenticação, autorização, validação de entrada).

### Avaliação
- **Design e Arquitetura**: Avaliação da estrutura do código e adesão aos princípios de SOLID, DDD e Clean Architecture.
- **Qualidade do Código**: Limpeza do código (Clean Code), organização, nomeação, comentários, e uso adequado de padrões de design.
- **Testes**: Cobertura e qualidade dos testes unitários e de integração.
- **Performance e Segurança**: Desempenho da API e boas práticas de segurança implementadas.
- **Observabilidade**: Avaliação da implementação de logs, monitoramento e métricas.
- **Entregas Técnicas**: Avaliar a consistência do pipeline CI/CD, uso de Docker e implantação no provedor de nuvem.

Boa sorte! Aguardamos sua solução 🚀.
