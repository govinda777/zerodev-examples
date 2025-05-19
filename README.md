# ZeroDev Token Shop

Uma interface simples implementada com ZeroDev para demonstrar funcionalidades de autenticação Ethereum, recompensas de tokens e uma loja virtual.

## Funcionalidades

- **Sistema de Login**: Autenticação usando ZeroDev para carteiras Ethereum
- **Sistema de Recompensa**: 10 tokens concedidos automaticamente no primeiro login
- **Loja de Produtos**: Lista de produtos que podem ser adquiridos usando tokens
- **Histórico de Compras**: Armazena e exibe as compras realizadas pelo usuário

## Tecnologias Utilizadas

- React / Next.js
- TypeScript
- Tailwind CSS
- ZeroDev para autenticação Web3
- Viem para interações com blockchain

## Configuração do Projeto

1. Clone o repositório:
```bash
git clone [URL_DO_REPOSITORIO]
cd zerodev-token-shop
```

2. Instale as dependências:
```bash
npm install
```

3. Crie um arquivo `.env.local` na raiz do projeto com o seguinte conteúdo:
```
NEXT_PUBLIC_RPC_URL=https://rpc-sepolia.rockx.com
```

4. Execute o projeto:
```bash
npm run dev
```

5. Acesse a aplicação em `http://localhost:3000`

## Como Usar

1. Clique no botão "Connect Wallet" para fazer login
2. No primeiro login, você receberá automaticamente 10 tokens
3. Navegue pela loja e compre produtos usando seus tokens
4. Consulte seu histórico de compras na parte inferior da página

## Observações

- Este projeto funciona na rede Ethereum Sepolia
- As operações são processadas através da infraestrutura ZeroDev, que facilita a experiência de uso de carteiras
- Os dados de usuário são armazenados localmente no navegador (localStorage)

## Licença

MIT