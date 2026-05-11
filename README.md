# 🚀 Projeto Gerador de QRCode e Password

Projeto desenvolvido durante o curso da DIO utilizando Node.js.

O sistema permite:

- ✅ Gerar QRCode no terminal
- ✅ Gerar senhas aleatórias
- ✅ Configurar tipos de caracteres usando arquivo `.env`
  
## Melhoria implementada:
- Adicionado sistema de classificação da força da senha (fraca, média e forte).

---

# 📚 Tecnologias Utilizadas

- Node.js
- JavaScript
- Prompt
- Chalk
- QRCode Terminal

---

#  Estrutura do Projeto

```bash
src/
│
├── prompts-schema/
│   ├── prompt-schema-main.js
│   └── prompt-schema-qrcode.js
│
├── services/
│   ├── password/
│   │   ├── create.js
│   │   ├── handle.js
│   │   └── utils/
│   │       └── permitted-characters.js
│   │
│   └── qr-code/
│       ├── create.js
│       └── handle.js
│
└── index.js

