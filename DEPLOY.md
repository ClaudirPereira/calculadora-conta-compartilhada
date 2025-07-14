# 🚀 Como Fazer Deploy no GitHub Pages

## 📋 Passo a Passo

### 1. **Criar Repositório no GitHub**
1. Acesse [GitHub.com](https://github.com)
2. Clique em "New repository"
3. Nome sugerido: `calculadora-conta-compartilhada`
4. Marque como "Public"
5. **NÃO** marque "Add a README file" (já temos um)
6. Clique em "Create repository"

### 2. **Fazer Upload dos Arquivos**

#### Opção A: Via Interface Web (Mais Fácil)
1. Na página do repositório criado, clique em "uploading an existing file"
2. Arraste todos os arquivos desta pasta para a área de upload
3. Escreva uma mensagem de commit: "Adicionar Calculadora Conta Compartilhada"
4. Clique em "Commit changes"

#### Opção B: Via Git (Linha de Comando)
```bash
# No terminal, dentro desta pasta:
git init
git add .
git commit -m "Adicionar Calculadora Conta Compartilhada"
git branch -M main
git remote add origin https://github.com/SEUUSUARIO/calculadora-conta-compartilhada.git
git push -u origin main
```

### 3. **Ativar GitHub Pages**
1. No repositório, vá em "Settings" (aba superior)
2. Role para baixo até "Pages" (menu lateral esquerdo)
3. Em "Source", selecione "Deploy from a branch"
4. Em "Branch", selecione "main"
5. Em "Folder", deixe "/ (root)"
6. Clique em "Save"

### 4. **Acessar o Site**
- Aguarde 2-5 minutos para o deploy
- Sua URL será: `https://SEUUSUARIO.github.io/calculadora-conta-compartilhada`
- O GitHub mostrará a URL na seção Pages

## 🔄 Atualizações Futuras

Para atualizar o site:
1. Faça as alterações nos arquivos
2. Faça commit e push para o repositório
3. O GitHub Pages atualizará automaticamente

## ✅ Verificação

Após o deploy, teste:
- [ ] Site carrega corretamente
- [ ] Configuração inicial funciona
- [ ] Novo registro funciona
- [ ] Cálculos estão corretos
- [ ] Exportação TXT funciona
- [ ] Responsivo no mobile

## 🆘 Problemas Comuns

### Site não carrega
- Verifique se GitHub Pages está ativado
- Aguarde alguns minutos após ativar
- Verifique se o arquivo `index.html` está na raiz

### Erro 404
- Confirme que o branch selecionado é "main"
- Verifique se os arquivos foram enviados corretamente

### Funcionalidades não funcionam
- Verifique se todos os arquivos da pasta `assets/` foram enviados
- Teste em modo incógnito para evitar cache

## 📞 Suporte

Se tiver problemas:
1. Verifique a aba "Actions" do repositório para ver logs de deploy
2. Teste localmente abrindo `index.html` no navegador
3. Consulte a [documentação do GitHub Pages](https://docs.github.com/en/pages)

