# Jogo da Forca

Um simpes jogo da forca, criado para praticar HTML, CSS, JavaScript e Git/Github. O código em si foi comentado, contendo a explicação de cada sessão relevante. Segue descrito neste arquivo os comandos Git utilizados para salvar o projeto no GitHub.

## Tópicos Abordados
* Criação de arquivos markdown (README.md)
* Uso de Git e Github para versionamento
* Criação de conteúdo através com HTML
* Estilização básica com CSS
* Uso de JavaScript para criar respostas à interação do usuário

## Comandos Git Utilizados
Após adicionado o projeto no Github e criada a token de acesso para o projeto, foram utilizados os comandos Git abaixo. Repare que este era um projeto bem simples, então acabei restrito a usar poucas funcionalidades do Git. Não foi necessário desfazer algum commit ou mesmo:

Ajusto as configurações da git no computador:
```csharp
git config --global user.name "Romulo Rocha Santos"
git config --global user.email "romulo.ciencia@gmail.com"
```

Crio, verifico o status do repositório e adiciono todos os arquivos da pasta
```csharp
git init
git status
```

Adiciono e verifico o repositório remoto (note que estou usando uma token de acesso)
```csharp
git remote add origin https://github.com/romulors/jogo-da-forca.git
git remote -v
```

Clono o repositório remoto, e quando houver novos arquivos, adiciono ao repositório local. Este comando clona o branch principal automaticamente (master, neste caso)
```csharp
git clone https://github.com/romulors/jogo-da-forca.git
git add *
```

Faço o commit dos arquivos, inserindo uma mensagem de texto curte e útil após o '-m'
```csharp
git commit -m "Mensagem curta e útil"
```

Envio os arquivos com commit do repositório local para o repositório remoto, no branch 'master'.
```csharp
git push origin master
```

Estes foram todos os comandos utilizados para este projeto simples. Para mais comandos (não utilizados neste caso), ver as informações adicionais!

## Comandos Markdown utilizados

### Ferramentas Utilizadas
* Editor de markdown: [Markdown Monster](https://markdownmonster.west-wind.com/)
* Editor de código: [Visual Studio Code](https://code.visualstudio.com/)
* Navegador Web: [Google Chrome](https://www.google.com/intl/pt-BR/chrome/) 
* Sistema de Versionamento: [Git](https://git-scm.com/)
* Hospedagem do código: [Github](https://github.com/)

### Informações Adicionais
* Criado por Romulo Rocha Santos
* Realizado em Janeiro de 2022
* Baseado no material desenvolvido [neste curso da Udemy](https://www.udemy.com/course/javascript-completo-html-css-projetos-profissionais/learn/lecture/22078102?start=0#overview)
* Github - [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
* Um bom guia prático com a listagens dos comandos e seus casos de uso pode ser encontrado [neste link](https://gist.github.com/leocomelli/2545add34e4fec21ec16).
