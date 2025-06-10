# 💬 Chat em Tempo Real com Múltiplas Salas (Socket.IO + Node.js)

Este é um projeto simples de chat em tempo real utilizando **Node.js**, **Express** e **Socket.IO**, com suporte para **múltiplas salas de conversa**. Os usuários podem escolher uma sala para entrar e trocar mensagens com outras pessoas na mesma sala.

---

## 📦 Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [Socket.IO](https://socket.io/)

---

## 🎯 Funcionalidades

- Seleção de uma entre 4 salas disponíveis.
- Envio e recebimento de mensagens em tempo real.
- Isolamento entre salas: somente quem está na mesma sala vê as mensagens.
- Interface simples e funcional para testes locais.

---

## 🖥️ Como Usar

### 1. Clonar o Repositório

```bash
git clone https://github.com/PedroAChaves/Chat-Socket
cd Chat-Socket
```

### 2. Instalar as Dependências

```bash
npm install
```

### 3. Iniciar o Servidor

```bash
npm start
```

O servidor será iniciado na porta `3000`. Acesse no navegador:

```
http://localhost:3000
```

---

## ✅ Como Testar

1. Abra **8 abas** no navegador.
2. Em cada par de abas, selecione uma **sala diferente** (Sala 1 a Sala 4).
3. Clique em **"Entrar na Sala"**.
4. Envie mensagens em cada aba.
5. As mensagens devem aparecer **somente** para quem estiver na **mesma sala**.

---

## 🗂️ Estrutura de Pastas

```
socket-chat/
├── public/
│   └── index.html       # Interface do usuário
├── index.js             # Servidor Node.js com Socket.IO
├── package.json         # Dependências e scripts
└── README.md            # Este arquivo
```

---

## 👨‍💻 Autor

Desenvolvido por Pedro Alexandre
RA: 2301503
GitHub: https://github.com/PedroAChaves