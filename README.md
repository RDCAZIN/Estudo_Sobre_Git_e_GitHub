
# DIO | Resumos Git e GitHub

Repositorios para armazenamento de resumos do curso de Versionamento de código com Git e GitHub, [LINK DO CURSO](https://web.dio.me/track/santander-2024-backend-com-java/course/versionamento-de-codigo-com-git-e-github)

## 📖 Documentação

- [GitHub](https://docs.github.com/pt)
- [Git](https://git-scm.com/docs/git/pt_BR)

## 📝 Resumos da Aula

| comando | Ação |
|---------|------|
|git init | Cria Repositorios|
|git status| Mostra se tem alguma os arquivos que foram alterados|
|git add .| Manda todos os arquivos alterados para a area de preparação|
|git add nome| Define o arquivo que vai ser enviado para a area de preparação
|git clone link do Repositorio| Clona o Repositorio|
|git remote add origin url_do_repositorio| vicula Repositorio remoto com local| 
|rm -rf .git| Remove o Git do arquivo|
|git commit --amend -m "mensagem"| Reescreve ultimo commit|
|git restore nome_do_arquivo| Volta arquivo para a ultima versao|
|git reset --soft hash_do_commit_anterior_ao_ultimo| Desfaz o ultimo commit, mantem de stage|
|git reset --mixed hash_do_commit| Desfaz o ultimo commit, fica fora do stage|
|git reset --hard hash_do_commit_anterior_ao_ultimo| Apaga todo o ulimo commit|
|git reset nome_do_arquivo| tira da area de stage o arquivo|
|git push -u origin main| manda pro Repositorio remoto (1° envio)|
|git push origin nome_branch| manda para o Repositorio remoto|
|git branch -M main|Força trocar master para main |
|git pull| pega as alterações do remoto|