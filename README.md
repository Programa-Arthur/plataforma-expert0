# Plataforma Expert

Repositório para versionamento da Plataforma Expert – sistema de monitoramento de sensores com Arduino, comunicação serial, WebSocket e interface web interativa.

# Como Executar

## Pré-requisitos

- Node.js
- Git
- NPM
- Arduino conectado via USB

## Passo a Passo

```bash
# 1. Clone o repositório
git clone https://github.com/Programa-Arthur/plataforma-expert0.git
cd plataforma-expert0

# 2. Instale as dependências
npm install

# 3. Inicie o servidor
# No Windows:
node server.js

# No Linux/macOS (pode precisar de sudo para acessar a porta serial):
sudo node server.js

# 4. Acesse no navegador
http://localhost:3000
