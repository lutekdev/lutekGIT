## Comandos Básicos
![alt](https://blog.da2k.com.br/uploads/2015/07/banner-git-e-github-ninja.jpg)
---

| Titulo                                              | Comando                                                                            |
| --------------------------------------------------- | ---------------------------------------------------------------------------------- |
| Configurando Seu Usuario Global                     | `git config --global user.name "."` - `git config --global user.email "."`         |
| Remover as Informações do Usuario Global            | `git config --global --unset user.name` - `git config --global --unset user.email` |
| Visualizar as Informações                           | `git config --global user.name` - `git config --global. user.email"`               |
| Para Visualizar a Lista de Configurações            | `git config --list`                                                                |
| Iniciando um Repositorio Numa Pasta                 | `git init`                                                                         |
| Mudar a Branch Principal para Outra (Personalizada) | `git config --global init.defaultBranch nome-da-branch`                            |
| Vendo o Status dos Commits Pendentes                | `git status`                                                                       |
| Adicionando Apenas Um Arquivo                       | `git add "nome-do-arquivo.extensao"`                                               |
| Adicionando Varios Arquivos                         | `git add .` - `git add --all` - `git add -A`                                       |
| Voltar as Alterações Do Arquivo                     | `git restore --staged nome-do-arquivo.extensao`                                    |
| Remover Apenas um Arquivo Adicionado                | `git rm --cached nome-do-arquivo.extensao`                                         |
| Remover Todos os Arquivos Adicionados               | `git rm --cached -r .`                                                             |
| Salvando Mudanças Nos Arquivos Adicionados          | `git commit -m "Mensagem"`                                                         |

---


