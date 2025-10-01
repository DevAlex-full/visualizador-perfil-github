# 🔍 Visualizador de Perfil do GitHub

![GitHub](https://img.shields.io/badge/GitHub-API-181717?style=for-the-badge&logo=github&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

Aplicação web interativa que permite buscar e visualizar perfis do GitHub, exibindo informações detalhadas sobre usuários e seus repositórios públicos.

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como exercício do curso **DevQuest 2.0**, com o objetivo de praticar conceitos de consumo de APIs, manipulação do DOM e desenvolvimento de interfaces responsivas.

A aplicação utiliza a API pública do GitHub para buscar dados de usuários e exibir de forma organizada informações como avatar, bio, seguidores e os 10 repositórios mais recentes.

## ✨ Funcionalidades

- 🔎 Busca de usuários do GitHub por username
- 👤 Exibição de informações do perfil (avatar, nome, bio)
- 📊 Contadores de seguidores e seguindo
- 📚 Listagem dos 10 repositórios mais recentes
- ⭐ Estatísticas de cada repositório (stars, forks, watchers, linguagem)
- 📱 Design totalmente responsivo
- 🎨 Interface moderna com gradiente animado
- ⌨️ Suporte para busca com tecla Enter

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização e animações
- **JavaScript (ES6+)** - Lógica e consumo de API
- **GitHub API** - Fonte de dados
- **CSS Variables** - Sistema de design tokens
- **Flexbox & Grid** - Layout responsivo
- **Fetch API** - Requisições HTTP

## 📁 Estrutura do Projeto

```
├── index.html
├── src/
│   ├── css/
│   │   ├── reset.css
│   │   ├── styles.css
│   │   ├── animations.css
│   │   └── responsive.css
│   └── js/
│       ├── index.js
│       ├── githubApi.js
│       └── profileView.js
```

## 🎯 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/DevAlex-full/github-profile-viewer.git
```

2. Navegue até o diretório do projeto:
```bash
cd github-profile-viewer
```

3. Abra o arquivo `index.html` no seu navegador ou use um servidor local:
```bash
# Exemplo usando Live Server no VS Code
# ou
python -m http.server 8000
```

4. Digite o username de qualquer usuário do GitHub e clique em "Buscar" ou pressione Enter.

## 💡 Aprendizados

Durante o desenvolvimento deste projeto, foram praticados os seguintes conceitos:

- Consumo de APIs REST
- Async/Await e Promises
- Módulos ES6 (import/export)
- Manipulação do DOM
- Tratamento de erros
- Design responsivo com media queries
- Animações CSS
- Organização de código em arquivos separados
- Boas práticas de desenvolvimento front-end

## 🎨 Destaques Visuais

- Background com gradiente animado em 5 cores
- Transições suaves em botões e cards
- Sistema de design consistente com variáveis CSS
- Cards de repositórios com hover effect
- Layout adaptável para todos os tamanhos de tela

## 📱 Responsividade

O projeto é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- 💻 Desktop (1280px+)
- 📱 Tablet (768px - 1024px)
- 📱 Mobile (320px - 767px)

## 🔗 Links

- [Meu GitHub](https://github.com/DevAlex-full)
- [GitHub API Documentation](https://docs.github.com/en/rest)

## 📝 Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso DevQuest 2.0.

---

⭐ Desenvolvido por [DevAlex](https://github.com/DevAlex-full) | DevQuest 2.0
