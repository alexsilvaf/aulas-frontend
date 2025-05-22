# Dicas úteis no git

Este documento reúne comandos e boas práticas básicas de Git para uso durante nossos estudos de Frontend.

---

## Configuração Inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

## Comandos essenciais

| Ação | Comentário | Comando |
|------|------------|---------|
| Clonar Repositório | | git clone https://github.com/seu-usuario/seu-repositorio.git |
| Status | Verifica o status do repositório | git status |
| Atualizar | Trará alterações do repositório remoto | git pull |
| Criar e mudar de branch | -b = nova branch caso não haja | git checkout -b nome-da-nova-branch |
| Deletar cache de senha salva pelo VSCode | Fará o VSCode deletar as senhas salvas  | git credential-cache exit
| Configurar VSCode para não salvar senhas | Configura o VSCode para não salvar mais as senhas | git config --global --unset credential.helper
| Mostra o histórico de commits | | git log |
| Mostra as diferenças entre arquivos | | git diff |
| Remove um arquivo do Git | | git rm <arquivo> |


## Enviar alterações (Push)
```bash
git add .
git commit -m "mensagem do commit"
git push
```