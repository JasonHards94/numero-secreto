
# Curso de Git e GitHub :octocat:

Bem-vindo ao repositório do **Curso de Git e GitHub**! Este curso foi criado para iniciantes que desejam aprender os fundamentos do controle de versão com o Git e como trabalhar com repositórios remotos no GitHub.

## 📋 Conteúdo

- Introdução ao Git e GitHub
- Instalação e configuração
- Conceitos fundamentais do Git
- Comandos básicos do Git
- Fluxo de trabalho com Git e GitHub
- Pull Requests e colaboração
- Branching e Merge
- Resolucão de conflitos

## 📸 Capturas de tela

### Exemplo de Interface do GitHub
![GitHub Interface](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

### Estrutura de Pastas do Repositório Local
![Estrutura de Pastas do Repositório](https://placekitten.com/600/400)

## ⚙️ Instalação

Antes de começar, é necessário instalar o Git. Você pode fazer o download a partir do site oficial:

[Download Git](https://git-scm.com/downloads)

Após a instalação, configure seu nome de usuário e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

## 💻 Comandos Básicos do Git

Aqui estão alguns comandos essenciais do Git que serão abordados no curso:

| Comando                     | Descrição                                                           |
|-----------------------------|---------------------------------------------------------------------|
| `git init`                  | Inicializa um repositório Git na pasta atual                        |
| `git clone <url>`           | Clona um repositório remoto para a máquina local                    |
| `git status`                | Mostra o status dos arquivos no repositório                         |
| `git add <arquivo>`         | Adiciona arquivos específicos ao estágio                           |
| `git commit -m "mensagem"`  | Confirma as mudanças com uma mensagem de commit                    |
| `git push`                  | Envia as mudanças para o repositório remoto                        |
| `git pull`                  | Atualiza o repositório local com as mudanças do repositório remoto |
| `git branch`                | Lista as branches disponíveis no repositório                       |
| `git checkout <branch>`     | Altera para uma branch específica                                  |
| `git merge <branch>`        | Mescla uma branch à branch atual                                   |

### Exemplo de Fluxo Básico
```bash
# Inicializar repositório local
git init

# Adicionar todos os arquivos ao staging
git add .

# Confirmar as mudanças
git commit -m "Primeiro commit"

# Conectar com um repositório remoto
git remote add origin <URL do Repositório>

# Enviar para o GitHub
git push -u origin main
```

## 🤝 Contribuindo

Sinta-se à vontade para contribuir! Para contribuir com melhorias, siga estas etapas:

1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b minha-nova-feature`).
3. Faça as alterações necessárias e commit (`git commit -m 'Adiciona minha feature'`).
4. Envie para o repositório remoto (`git push origin minha-nova-feature`).
5. Abra um Pull Request.

## 📜 Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

---

> Feito com 💖 por [Seu Nome]
