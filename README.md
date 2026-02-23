# 📄 DocFlow — PDF Manager

App de manipulação de PDFs 100% no navegador, com interface corporativa clean.

## ✨ Funcionalidades

- **Excluir páginas** — clique individual ou selecione múltiplas e exclua em lote
- **Reordenar páginas** — arrastar e soltar (drag & drop) ou botões ▲ ▼
- **Inserir páginas** — insira PDFs no início, fim ou posição específica
- **Exportar** — baixe o PDF final reorganizado

## 🚀 Deploy na Vercel

### Opção 1 — Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

### Opção 2 — Vercel Dashboard
1. Acesse [vercel.com](https://vercel.com)
2. Clique em **Add New Project**
3. Faça upload da pasta ou conecte ao GitHub
4. Deploy automático — sem configuração extra

### Opção 3 — GitHub + Vercel
1. Suba os arquivos para um repositório GitHub
2. No Vercel, importe o repositório
3. Framework: **Other** (site estático)
4. Build command: *(vazio)*
5. Output directory: `.`

## 🛠 Desenvolvimento local

```bash
npx serve . -p 3000
# Acesse http://localhost:3000
```

## 🔧 Stack Técnica

| Tecnologia | Uso |
|---|---|
| **pdf-lib** | Manipulação e exportação de PDFs |
| **PDF.js** | Renderização de thumbnails |
| **HTML/CSS/JS** | Interface — sem dependências de build |
| **Vercel** | Hospedagem estática |

> Todo o processamento é **100% client-side** — nenhum arquivo é enviado a servidores.
