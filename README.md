# Desafio Backend
**Parabéns!**
Ficamos muito felizes por você ter chegado até aqui. Agora é hora de botar as mãos 
no código e mostrar como você pensa, estrutura e documenta seu trabalho.

## O desafio

Nosso desafio contempla uma situação real do cotidiano dos operadores de pontos de 
venda (PDV).

Esses profissionais têm grande responsabilidade em suas mãos: a maior parte do seu 
tempo é gasta recebendo valores de clientes e, em alguns casos, fornecendo troco.

Seu desafio é criar uma API que:
- Receba o valor total a ser pago e o valor efetivamente pago pelo cliente
- Informe o menor número de cédulas e moedas a serem fornecidas como troco
- Registre cada transação para consulta posterior

O sistema será utilizado por múltiplos operadores simultaneamente. 
Considere isso nas suas decisões arquiteturais.

## Regras

- Moedas: R$ 0,05 (cinco centavos), R$ 0,10 (dez centavos), R$ 0,25 (vinte e cinco centavos), R$ 0,50 (cinquenta centavos) e R$ 1,00 (um real).
- Cédulas (notas): R$ 2, R$ 5, R$ 10, R$ 20, R$ 50, R$ 100 e R$ 200.
- Entregar sempre o menor número de cédulas e moedas possível.

**Exemplos:**

| Troco | Resultado esperado |
|-------|--------------------|
| R$ 30,00 | 1 nota de R$ 20,00 + 1 nota de R$ 10,00 |
| R$ 80,00 | 1 nota de R$ 50,00 + 1 nota de R$ 20,00 + 1 nota de R$ 10,00 |
| R$ 0,75 | 1 moeda de R$ 0,50 + 1 moeda de R$ 0,25 |

## Requisitos obrigatórios

- .NET 10
- Registro de todas as transações de troco (operador, valor pago, valor total, 
  troco calculado, data/hora)
- Consulta do histórico de transações filtrando por período
- Tratamento adequado de entradas inválidas (valor pago menor que o total, 
  valores negativos, valores zerados)
- Testes unitários
- Swagger para documentação das rotas
- Docker / docker-compose

## O que será avaliado

- Estrutura e organização do código
- Qualidade e clareza do código
- Boas práticas e padrões utilizados
- Tratamento de erros e casos de borda
- **README com suas decisões arquiteturais** — conte por que você estruturou 
  o projeto dessa forma e quais trade-offs considerou.

## Dicas

- Tente não fazer tudo em um único commit.
- O README importa tanto quanto o código — é onde vemos como você pensa.
- Versione seu teste no GitHub, através de um repositório que será criado por nós e compartilhado com você
- Assim que terminar, envie um e-mail com o link do repositório e não faça mais commits depois disso.

**Boa sorte! Estamos ansiosos para ter você no time.**
