# 🔐 login-protegido

Sistema simples de login integrado com **Google Sheets + Apps Script**.

## 🧱 Estrutura
- login.html → tela de login
- painel.html → página protegida
- auth.js → script de verificação
- index.html → redireciona para login

## ⚙️ Como usar
1. Crie uma planilha com a aba **Usuarios_Autorizados**  
   Colunas: Nome | Email | Senha | NivelAcesso
2. Adicione usuários.
3. Vincule o Apps Script e publique como Web App.
4. Atualize API_URL dentro de login.html.
5. Publique no GitHub Pages.
