# changemap
A technology solution for mapping device changes in a network environment.

# ChangeMap Web (via Google Sheets)

Este projeto é uma interface web simples que permite executar comparações entre abas de uma planilha Google via Apps Script e visualizar os resultados em uma página HTML com visual moderno.

## ✅ Como funciona

1. O usuário acessa o `index.html`.
2. Informa as abas (ex: Jan2025 e Fev2025).
3. Clica no botão "Executar Comparação".
4. O sistema redireciona para o Web App do Google Apps Script que:
   - Executa a comparação entre abas
   - Atualiza a aba `Relatório` na planilha
   - Exibe um relatório estilizado em HTML

## 🔗 Web App do Google Apps Script

Altere a URL do script no `index.html` se você atualizar sua implantação:

```
https://script.google.com/macros/s/SEU_DEPLOYMENT_ID/exec
```

## 📦 Publicação

Você pode subir este conteúdo no GitHub Pages, Vercel, Netlify ou qualquer hospedagem de arquivos estáticos.

