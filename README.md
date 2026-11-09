# Black Imports00

Site estático (HTML/CSS/JS puro) da loja Black Imports00.

## Estrutura
- `index.html` – página única
- `assets/` – imagens
- `vercel.json` – cache e cabeçalhos de segurança

## Deploy (GitHub → Vercel)
1. Crie um repositório no GitHub e envie estes arquivos:
   ```bash
   git init
   git add .
   git commit -m "Primeiro commit"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/black-imports00.git
   git push -u origin main
   ```
2. Em vercel.com → **Add New → Project** → importe o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios (raiz do projeto).
4. Clique em **Deploy**. Cada `git push` na `main` publica automaticamente.
