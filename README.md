# Partido-Brasileiro-da-Autonomia-Libertaria-Minarquista

O PBALM é uma proposta de nome que combina identidade nacional, autonomia individual, libertarianismo e minarquismo. Pode servir como ponto de partida para um partido que reúna liberais clássicos, minarquistas, libertários e anarcocapitalistas.

Este projeto está em desenvolvimento. O código HTML está disponível no repositório e pode ser copiado e adaptado para uso.
Autor: Nedir da Silva França Júnior. @juniorjfsny
Presidente do Partido : Nedir da Silva França Júnior.

## Observações

Estas são as identidades e e-mails informados para uso em configurações locais do Git:

```bash
user.name = "juniorjrfsn"
user.email = "junior.jrfsn@gmail.com"

user.name = "juniorjrfsnt"
user.email = "junior.jrfsn@tutanota.com"

user.name = "juniornsfjt"
user.email = "junior.nsfj@tutamail.com"

user.name = "juniorjrfsnp"
user.email = "junior.jrfsn@protonmail.com"

user.name = "juniormodalpixp"
user.email = "junsfjmodalpix@protonmail.com"

user.name = "juniornsfjtg"
user.email = "juniornsfjt@gmail.com"

user.name = "juniorjrfsntg"
user.email = "juniorjrfsnt@gmail.com"

user.name = "juniornsfjp"
user.email = "junior.nsfj@protonmail.com"

user.name = "junsfjsantanderpixp"
user.email = "junsfjsantanderpix@protonmail.com"

user.name = "junsfjsantanderpixp"
user.email = "junsfjsantanderpix@protonmail.com"

user.name = "juniorjrfsnpg"
user.email = "juniorjrfsnp@gmail.com"

user.name = "juniorjfsnpg"
user.email = "juniorjfsnp@gmail.com"

user.name = "juniornsfjg"
user.email = "junior.nsfj@gmail.com"

user.name = "juniornsfjpg"
user.email = "juniornsfjp@gmail.com"

user.name = "juniornsfp"
user.email = "junior.nsf@protonmail.com"

user.name = "juniorjrdeepseekg"
user.email = "junior.jrdeepseek@gmail.com"

user.name = "juniornsfy"
user.email = "junior.nsf@yahoo.com"

user.name = "juniorjfsny"
user.email = "junior.jfsn@yahoo.com"
```

#### Repositório Globais
``` 
git config --global user.name "juniorjfsny"
git config --global user.email "junior.jfsn@yahoo.com"
```

#### Repositório
``` 
git config user.name "juniorjfsny"
git config user.email "junior.jfsn@yahoo.com"
``` 

# PBALM

contato:<junior.jfsn@yahoo.com>

```
git config user.name "juniorjfsny"
git config user.email "junior.jfsn@yahoo.com"
```

### logon GitHub

```
git remote -v; git status -sb; if command -v gh >/dev/null 2>&1; then gh auth status; else printf '\nGitHub CLI (gh) não está instalado.\n'; fi
```

#### GitHub CLI
``` 
winget install --id GitHub.cli --exact

```


```
gh auth login --hostname github.com --git-protocol https --web
```

```
gh auth status
```

```
git push origin main
```

#### Logar em uma conta no GitHub
```
gh auth login
```

Alternar entre as contas
Para ativar a conta juniorjrfsn, execute:

```
gh auth switch --user juniorjrfsn
```

Para voltar à conta juniorjfsny:
```
gh auth switch --user juniorjfsny
```

Confira qual conta está ativa:
```
gh auth status
```


2. Remover uma conta do GitHub CLI
Se você quiser desconectar a conta juniorjrfsn, execute:
```
gh auth logout --hostname github.com --user juniorjfsny
gh auth logout --hostname github.com --user juniorjrfsn
```


Confirme a operação se o CLI solicitar.

Atenção: isso remove a autenticação dessa conta no GitHub CLI, mas não necessariamente a desconecta do VS Code ou remove todas as credenciais armazenadas no Windows.
3. Verificar qual conta o Git usa nos seus projetos
Dentro da pasta do projeto, execute:
```
git config user.name
git config user.email
git remote -v
```
