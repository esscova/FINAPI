# API REST Finanças
![print](/public/images/print.png)

>Exemplo de API REST simples que permite a criação, consulta e gerenciamento de contas bancárias de clientes, incluindo depósitos, saques, obtenção de extratos, verificação de saldo e outras operações bancárias básicas conforme requisitos e regras de negócio sugeridas abaixo:


### Requisitos
- Deve ser possível criar uma conta
- Deve ser possível buscar o extrato bancário do cliente
- Deve ser possível realizar um depósito
- Deve ser possível realizar um saque
- Deve ser possível buscar o extrato bancário do cliente por data
- Deve ser possível atualizar dados da conta do cliente
- Deve ser possível obter dados da conta do cliente
- Deve ser possível deletar uma conta
- Dever ser possível retornar o saldo

### Regras do negócio
 - Não deve ser possível cadastrar um conta com CPF já existente
 - Não deve ser possível fazer depósito em uma conta não existente
 - Não deve ser possível buscar extrato em uma conta não existente
 - Não deve ser possível fazer saque em uma conta não existente
 - Não deve ser possível excluir uma conta não existente
 - Não deve ser possível fazer saque quando o saldo for insuficiente
 - Não deve ser possível retornar o saldo quando a conta for inexistente

 ## Tecnologias
 - NodeJS
 - ExpressJS
 - Nodemon
 - Insomnia

 ## Aprendizado e considerações
 Neste treinamento sobre API aprendi como se permite a criação de contas (/account), consulta de extratos (/statement), depósitos (/deposit), saques (/withdraw), atualização de dados da conta (/account), exclusão de contas (/account), obtenção de saldo (/balance), e consulta de extrato por data (/statement/date).

 Também vale notar que o código está configurado para usar um array em memória para armazenar dados das contas.

 Por fim aprendi também a praticidade de middleware que no código por exemplo, verifica se uma conta com o CPF fornecido existe antes de permitir que outras rotas sejam acessadas.

## 🛸 Dove puoi trovarmi
 [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wellington-moreira-santos)


 [![Telegram]( https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/welligton_moreira_santos)