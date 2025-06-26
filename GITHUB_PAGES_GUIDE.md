# 📚 Guia Completo: Como Colocar o Site no GitHub Pages

## 🎯 Pré-requisitos

- Conta no GitHub (gratuita)
- Git instalado no seu computador
- Projeto organizado (já está pronto!)

## 📋 Passo a Passo Detalhado

### 1️⃣ **Inicializar o Repositório Git**

Abra o terminal no diretório do projeto e execute:

```bash
# Navegar até o diretório do projeto
cd "e:\Projetos VScode\siteFeiraUberaba"

# Inicializar o repositório Git
git init

# Adicionar todos os arquivos
git add .

# Fazer o primeiro commit
git commit -m "🚀 Initial commit: Site Feiras do Bairro Uberaba"
```

### 2️⃣ **Criar Repositório no GitHub**

1. Acesse [github.com](https://github.com)
2. Faça login na sua conta
3. Clique no botão **"New repository"** (verde)
4. Preencha as informações:
   - **Repository name**: `feira-uberaba-site` (ou outro nome de sua preferência)
   - **Description**: "Site moderno para divulgação das feiras livres de Uberaba"
   - Marque como **Public** (necessário para GitHub Pages gratuito)
   - **NÃO** marque "Add a README file" (já temos um)
5. Clique em **"Create repository"**

### 3️⃣ **Conectar Repositório Local ao GitHub**

No terminal, execute (substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub):

```bash
# Adicionar o repositório remoto
git remote add origin https://github.com/SEU_USUARIO/feira-uberaba-site.git

# Enviar os arquivos para o GitHub
git branch -M main
git push -u origin main
```

### 4️⃣ **Ativar GitHub Pages**

1. No seu repositório no GitHub, clique na aba **"Settings"**
2. Role para baixo até encontrar **"Pages"** no menu lateral
3. Em **"Source"**, selecione **"Deploy from a branch"**
4. Em **"Branch"**, selecione **"main"**
5. Em **"Folder"**, deixe **"/ (root)"**
6. Clique em **"Save"**

### 5️⃣ **Aguardar Deploy**

- O GitHub levará alguns minutos para fazer o deploy
- Você receberá um link como: `https://seuusuario.github.io/feira-uberaba-site/`
- O site estará disponível globalmente!

## 🔧 Comandos para Atualizações Futuras

Sempre que você fizer alterações no site:

```bash
# Adicionar as mudanças
git add .

# Fazer commit das alterações
git commit -m "✨ Descrição da alteração"

# Enviar para o GitHub
git push origin main
```

## ⚡ Comandos Prontos para Copy/Paste

**Primeiro setup:**
```bash
cd "e:\Projetos VScode\siteFeiraUberaba"
git init
git add .
git commit -m "🚀 Initial commit: Site Feiras do Bairro Uberaba"
```

**Após criar o repositório no GitHub:**
```bash
git remote add origin https://github.com/SEU_USUARIO/feira-uberaba-site.git
git branch -M main
git push -u origin main
```

## 🌟 Dicas Importantes

1. **Nome do Repositório**: Use nomes descritivos como `feira-uberaba`, `site-feiras-uberaba`
2. **Público vs Privado**: Para GitHub Pages gratuito, o repositório deve ser público
3. **Arquivo Principal**: O `index.html` que criamos redireciona automaticamente para `index_novoFeira.html`
4. **Tempo de Deploy**: Primeiros deploys podem levar até 10 minutos
5. **Cache**: Mudanças podem demorar alguns minutos para aparecer devido ao cache

## 🎨 URLs Finais

Após o deploy, seu site estará disponível em:
- **URL Principal**: `https://seuusuario.github.io/nome-do-repositorio/`
- **URL Direta**: `https://seuusuario.github.io/nome-do-repositorio/index_novoFeira.html`

## 🚨 Solução de Problemas

**Se algo der errado:**

1. **Erro 404**: Verifique se o repositório é público e se o GitHub Pages está ativado
2. **Site não carrega**: Aguarde alguns minutos e limpe o cache do navegador
3. **Imagens não aparecem**: Verifique se todos os arquivos da pasta `imgs/` foram enviados
4. **Comandos Git não funcionam**: Verifique se o Git está instalado e configurado

## 📞 Suporte

Se precisar de ajuda adicional, você pode:
1. Verificar a documentação oficial do [GitHub Pages](https://pages.github.com/)
2. Consultar o status do GitHub em [githubstatus.com](https://www.githubstatus.com/)

---

**🎉 Parabéns! Seu site estará online e acessível para o mundo todo!**
