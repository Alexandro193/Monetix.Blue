# Monetix.Blue
Venda automática trafego
const express = require('express');
const app = express();
const PORT = process.env.PORT || 3000;

app.get('/', (req, res) => {
  res.send('🚀 Monetix.Blue está funcionando automaticamente!');
});

app.listen(PORT, () => {
  console.log(`Servidor rodando na porta ${PORT}`);
});{
  "name": "monetix-blue",
  "version": "1.0.0",
  "description": "Automação de tráfego e vendas afiliadas",
  "main": "index.js",
  "scripts": {
    "start": "node index.js"
  },
  "dependencies": {
    "express": "^4.18.2"
  }
}
