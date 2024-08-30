# DIO Coin - ERC20 Token

Este repositório contém o código do contrato inteligente Solidity para o token "DIO Coin" (símbolo: DIO), um token ERC20 padrão na Ethereum. O contrato inclui funcionalidades básicas para um token ERC20, como transferência de tokens, aprovação para gastar tokens em nome de outro usuário, e outras funcionalidades básicas conforme o padrão ERC20.

## Descrição do Contrato

O contrato "DIOToken" é um exemplo de implementação de um token ERC20 na rede Ethereum. Ele foi desenvolvido usando a linguagem Solidity e inclui métodos seguros de matemática (SafeMath) para evitar overflow e underflow.

### Funcionalidades Principais

- **Transferência de Tokens:** Permite que os usuários transfiram tokens para outros endereços.
- **Aprovação de Gastos:** Permite que o dono dos tokens aprove o uso de uma quantidade específica de tokens para outra conta.
- **Transferência de Tokens por Terceiros:** Permite a transferência de tokens entre dois usuários, autorizada por um deles.
- **Consulta de Saldo e Suprimento Total:** Consulta o saldo de um endereço específico e o total de tokens disponíveis.
- **Segurança Melhorada com SafeMath:** Uso de funções seguras de matemática para prevenir erros de overflow e underflow.

### Funcionalidades Adicionais

- **Função `approveAndCall`:** Permite que um contrato aprovado execute uma operação após a aprovação do gasto de tokens.
- **Rejeição de Ether:** O contrato rejeita explicitamente qualquer Ether enviado, revertendo a transação para evitar qualquer uso indevido.

## Pré-requisitos

- Solidity `>=0.8.2 <0.9.0`
- Node.js (opcional, para ferramentas de desenvolvimento)
- Hardhat ou Truffle (para desenvolvimento e testes)


