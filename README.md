# Loading Desbloqueio Cartão - Havan

Loading animado para desbloqueio de cartão de crédito Havan, hospedado no Railway com proporções 330x200px.

## 🚀 Como Fazer Deploy no Railway

### Pré-requisitos

- Conta no [Railway.app](https://railway.app)
- Repositório GitHub com os arquivos do projeto

### Passos para Deploy

1. **Criar um novo projeto no Railway**
   - Acesse [railway.app](https://railway.app)
   - Clique em "New Project"
   - Selecione "Deploy from GitHub"
   - Selecione este repositório

2. **Railway detectará automaticamente**
   - O projeto será identificado como Node.js
   - O deploy começará automaticamente

3. **Acessar a URL**
   - Você receberá uma URL como: `https://seu-projeto-xxxxx.railway.app`

## 📝 Estrutura do Projeto

```
.
├── loading_desbloqueio.html  # Arquivo HTML do loading
├── package.json              # Configuração Node.js
├── server.js                 # Servidor HTTP simples
└── README.md                 # Este arquivo
```

## 🔗 URLs de Acesso

Após o deploy, você poderá acessar:

- **URL Principal**: `https://seu-projeto.railway.app/`
- **URL Direta**: `https://seu-projeto.railway.app/loading_desbloqueio.html`

## 💡 Usando no Typebot

1. Copie a URL do seu projeto Railway
2. No Typebot, adicione um bloco de **Embed (HTML/Iframe)**
3. Cole a URL do loading
4. Configure o tamanho conforme necessário

## 🛠️ Desenvolvimento Local

Para testar localmente:

```bash
npm install
npm start
```

Acesse `http://localhost:3000/loading_desbloqueio.html`

## 📋 Características

- ✅ Loading de 8 segundos
- ✅ Sem looping
- ✅ Proporções: 330x200px
- ✅ Centralizado
- ✅ Alta qualidade
- ✅ Cores Havan (azul #003d7a e verde #00a86b)
- ✅ CORS habilitado para uso em iframes

## 🎬 Animação

A animação possui 3 fases:

1. **0-5 segundos**: Spinner girando com logo H e mensagem "Desbloqueando cartão de crédito"
2. **5-5.5 segundos**: Transição suave
3. **5.5-8 segundos**: Checkmark verde com mensagem "CARTÃO DE CRÉDITO DESBLOQUEADO!" (e para aqui, sem looping)

## 📞 Suporte

Se tiver dúvidas sobre o Railway, consulte a [documentação oficial](https://docs.railway.app)

---

**Desenvolvido com ❤️ para Havan**
