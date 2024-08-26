# Mapeando domínios (DDD)
 Exercício - Mapeando Domínios - DDD no Node.js - Rocketseat

### O que fazer?

Nessa atividade você irá ler uma conversa entre um Domain Expert e um desenvolvedor responsável por criar a aplicação. O seu objetivo é identificar as entidades e casos de uso para essa aplicação com base nessa conversa!

### Entrevista

Leia a entrevista no arquivo ENTREVISTA.MD

### O que você deve procurar?

Dado o diálogo acima, você deve conseguir responder as seguintes perguntas:

- Quais as entidades de domínio?
- Quais as ações (casos de uso) que essa aplicação deve ter?

## Resposta

#### Quais as entidades de domínio?
- produto
- estoque
- vendas
- ordem_compra
- alertas

#### Quais as ações (casos de uso) que essa aplicação deve ter?
- rastrear produto por identificador único
- definir limite mínimo para cada produto
- definir quantidades mínimas de estoque
- alertas para quando estiver ficando sem um determinado produto
- adicionar informações extras no produto (cor e tamanho) 
- métricas de vendas 
- métricas de estoque
- criar ordem de compra com base nas quantidades mínimas de estoque
- criar nova venda 