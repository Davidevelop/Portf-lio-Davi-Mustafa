# 🚀 Guia de Deploy - Portfólio Davi Mustafa

## 📋 Passo a Passo para Subir o Portfólio para a Web

### 1️⃣ Preparar o Repositório Local

```bash
# Inicializar o Git
git init

# Adicionar todos os arquivos
git add .

# Fazer o primeiro commit
git commit -m "feat: portfólio profissional completo com tema escuro e responsivo"

# Renomear branch para main
git branch -M main
```

### 2️⃣ Conectar com o GitHub

```bash
# Adicionar o repositório remoto
git remote add origin https://github.com/Davidevelop/Portf-lio-Davi-Mustafa.git

# Verificar se foi adicionado corretamente
git remote -v

# Fazer o push inicial
git push -u origin main
```

### 3️⃣ Configurar GitHub Pages

1. **Acesse seu repositório no GitHub**: https://github.com/Davidevelop/Portf-lio-Davi-Mustafa

2. **Vá em Settings** (configurações)

3. **Role até "Pages"** no menu lateral

4. **Em "Source"**, selecione:
   - **Deploy from a branch**
   - **Branch**: `main`
   - **Folder**: `/ (root)`

5. **Clique em "Save"**

6. **Aguarde alguns minutos** para o GitHub processar

7. **Seu portfólio estará disponível em**: 
   ```
   https://davidevelop.github.io/Portf-lio-Davi-Mustafa/
   ```

### 4️⃣ Comandos para Atualizações Futuras

```bash
# Adicionar mudanças
git add .

# Fazer commit
git commit -m "descrição da mudança"

# Enviar para o GitHub
git push origin main
```

### 5️⃣ Verificar se Está Funcionando

- ✅ Acesse: https://davidevelop.github.io/Portf-lio-Davi-Mustafa/
- ✅ Teste em diferentes dispositivos
- ✅ Verifique se todas as imagens carregam
- ✅ Teste os links de contato

### 6️⃣ Personalizar o Domínio (Opcional)

Se quiser um domínio personalizado:

1. **Compre um domínio** (ex: davimustafa.com.br)
2. **No GitHub Pages**, adicione o domínio em Settings > Pages
3. **Configure o DNS** do seu domínio para apontar para o GitHub

### 🔧 Troubleshooting

**Problema**: Site não carrega
- **Solução**: Aguarde 5-10 minutos após o push

**Problema**: Imagens não aparecem
- **Solução**: Verifique se os caminhos das imagens estão corretos

**Problema**: CSS não aplica
- **Solução**: Verifique se o arquivo styles.css está no repositório

### 📱 Teste de Responsividade

- **Desktop**: Chrome, Firefox, Safari
- **Mobile**: iPhone, Android
- **Tablet**: iPad, Android tablets

### 🎯 Próximos Passos

1. **Compartilhe o link** com recrutadores
2. **Adicione ao seu LinkedIn** como website
3. **Inclua no currículo** como portfólio online
4. **Monitore o GitHub** para ver quem visualiza

---

**🎉 Parabéns! Seu portfólio está no ar!**

*Link do seu portfólio: https://davidevelop.github.io/Portf-lio-Davi-Mustafa/*
