# Sam Inglês — PWA

## Publicar no GitHub Pages (grátis)
1. Crie um repositório público no GitHub, por exemplo `sam-ingles`.
2. Envie todos os arquivos desta pasta para a raiz do repositório (pode arrastar em "Add file → Upload files").
3. Em Settings → Pages: Source = "Deploy from a branch", Branch = `main`, pasta `/ (root)`. Salve.
4. Em 1–2 minutos o app fica em `https://SEU-USUARIO.github.io/sam-ingles/`.

## Instalar no celular
- Android (Chrome): abra o link → menu ⋮ → "Instalar app" / "Adicionar à tela inicial".
- iPhone (Safari): abra o link → Compartilhar → "Adicionar à Tela de Início".

## Chave do Gemini
1. aistudio.google.com → "Get API key" → "Create API key".
2. No app: Configurações → "Google Gemini · grátis" → cole a chave → Salvar.
3. Recomendado: em console.cloud.google.com → APIs e serviços → Credenciais → sua chave →
   "Restrições de aplicativo: Sites da Web" → adicione `https://SEU-USUARIO.github.io/*`
   e em "Restrições de API" deixe só "Generative Language API".

## Atualizar o app
Envie o novo `index.html` e troque `sam-ingles-v1` por `sam-ingles-v2` no `sw.js`.
