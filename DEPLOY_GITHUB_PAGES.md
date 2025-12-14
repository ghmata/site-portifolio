# 🚀 Guia Completo: Deploy no GitHub Pages

Este guia vai te ajudar a colocar seu portfólio **online HOJE** usando GitHub Pages (100% gratuito).

---

## 📋 Pré-requisitos

1. **Conta no GitHub** (se não tiver, crie em [github.com](https://github.com))
2. **Git instalado** no seu computador
   - Verifique digitando no terminal: `git --version`
   - Se não tiver, baixe em: [git-scm.com](https://git-scm.com/)

---

## 🎯 Passo a Passo (Método Simples)

### **Passo 1: Criar Repositório no GitHub**

1. Acesse [github.com](https://github.com) e faça login
2. Clique no botão **"New"** (ou ícone **+** no canto superior direito → **New repository**)
3. Preencha os dados:
   - **Repository name:** `portfolio` (ou qualquer nome que preferir)
   - **Description:** `Meu portfólio profissional - Desenvolvedor Fullstack`
   - **Visibilidade:** Marque **Public** (obrigatório para GitHub Pages gratuito)
   - **NÃO** marque "Add a README file"
4. Clique em **"Create repository"**

---

### **Passo 2: Preparar Pasta de Imagens (Opcional)**

Se você já tiver screenshots dos seus projetos:

1. Na pasta do seu portfólio, crie uma pasta chamada `images`
2. Adicione as imagens com os nomes exatos:
   - `concan.png` (800x450px recomendado)
   - `locamil.png` (800x450px recomendado)
   - `comrec.png` (600x400px recomendado)

**Se não tiver as imagens agora, sem problemas!** O site vai mostrar placeholders elegantes até você adicionar.

---

### **Passo 3: Subir o Código para o GitHub**

Abra o **Terminal** (PowerShell no Windows) e navegue até a pasta do seu projeto:

```powershell
cd "C:\Users\gabri\OneDrive\Desktop\Freela\Portifólio - Automações\site_portifolio"
```

Agora execute os comandos abaixo **um por vez**:

#### 1. Inicializar o Git na pasta
```powershell
git init
```

#### 2. Adicionar todos os arquivos
```powershell
git add .
```

#### 3. Fazer o primeiro commit
```powershell
git commit -m "Primeiro commit - Portfólio online"
```

#### 4. Renomear a branch para 'main'
```powershell
git branch -M main
```

#### 5. Conectar ao repositório remoto
**⚠️ IMPORTANTE:** Substitua `SEU_USUARIO` pelo seu nome de usuário do GitHub e `portfolio` pelo nome do repositório que você criou.

```powershell
git remote add origin https://github.com/SEU_USUARIO/portfolio.git
```

**Exemplo real:**
```powershell
git remote add origin https://github.com/ghmata/portfolio.git
```

#### 6. Enviar o código para o GitHub
```powershell
git push -u origin main
```

**Nota:** Na primeira vez, o Git pode pedir suas credenciais do GitHub. Digite seu usuário e senha (ou token de acesso pessoal).

---

### **Passo 4: Ativar o GitHub Pages**

1. No navegador, vá até o repositório que você acabou de criar
2. Clique na aba **"Settings"** (Configurações)
3. No menu lateral esquerdo, clique em **"Pages"**
4. Em **"Source"**, selecione:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Clique em **"Save"**

**Aguarde 1-2 minutos** e recarregue a página. Você verá uma mensagem:

```
✅ Your site is live at https://SEU_USUARIO.github.io/portfolio/
```

---

## 🎉 Pronto! Seu Portfólio Está Online!

Acesse a URL que apareceu (exemplo: `https://ghmata.github.io/portfolio/`)

---

## 🔧 Atualizações Futuras

Sempre que você quiser atualizar o site (adicionar imagens, mudar textos, etc.):

1. Faça as alterações nos arquivos locais
2. No terminal, execute:

```powershell
git add .
git commit -m "Descrição da atualização"
git push
```

3. Aguarde 1-2 minutos e as mudanças estarão online!

---

## 📝 Checklist Final

Antes de compartilhar seu portfólio, verifique:

- [ ] **Número do WhatsApp** está correto (substitua `5511999999999` no código)
- [ ] **Links do GitHub** estão funcionando
- [ ] **Imagens dos projetos** foram adicionadas (ou placeholders estão OK)
- [ ] Testou em **mobile** (abra no celular)
- [ ] Todos os links abrem em **nova aba**

---

## 🆘 Problemas Comuns

### **"Permission denied" ao fazer push**
- Você precisa configurar autenticação. Use um **Personal Access Token** em vez de senha.
- Tutorial: [docs.github.com/authentication](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

### **Site não aparece após ativar Pages**
- Aguarde 2-5 minutos (pode demorar um pouco na primeira vez)
- Verifique se a branch está como `main` e a pasta como `/ (root)`

### **Imagens não aparecem**
- Certifique-se de que a pasta `images` está no mesmo nível do `index.html`
- Os nomes dos arquivos devem ser exatamente: `concan.png`, `locamil.png`, `comrec.png`

---

## 🎯 Domínio Personalizado (Opcional)

Se você quiser usar um domínio próprio (ex: `gabrielhipolito.com.br`):

1. Compre um domínio (Registro.br, Hostinger, etc.)
2. No GitHub Pages, adicione o domínio customizado
3. Configure os DNS do domínio apontando para o GitHub

Tutorial oficial: [docs.github.com/pages/configuring-a-custom-domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

---

## 📱 Compartilhe Seu Portfólio

Depois que estiver online, compartilhe em:

- ✅ LinkedIn (atualize seu perfil com o link)
- ✅ WhatsApp Status
- ✅ Grupos de Freelancers
- ✅ Seu currículo

---

**Boa sorte! 🚀**

Se tiver qualquer dúvida, consulte a documentação oficial do GitHub Pages:
[docs.github.com/pages](https://docs.github.com/en/pages)
