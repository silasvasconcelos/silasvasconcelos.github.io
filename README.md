# silasvasconcelos.com

Site pessoal desenvolvido com [Hugo](https://gohugo.io/) usando o tema [PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## 🚀 Tecnologias

- **Hugo** - Framework estático para sites
- **PaperMod** - Tema moderno e responsivo para Hugo

## 📋 Pré-requisitos

- [Hugo](https://gohugo.io/installation/) (versão 0.146.0 ou superior)
- Git

## 🛠️ Instalação

1. Clone o repositório:
```bash
git clone <repository-url>
cd silasvasconcelos
```

2. O tema PaperMod já está incluído no diretório `themes/`. Se necessário, você pode atualizá-lo usando Git submodules:
```bash
git submodule update --init --recursive
```

## 🏃 Executando Localmente

Para executar o site em modo de desenvolvimento:

```bash
hugo server
```

O site estará disponível em `http://localhost:1313`

Para gerar os arquivos estáticos:

```bash
hugo
```

Os arquivos serão gerados no diretório `public/`.

## 📁 Estrutura do Projeto

```
.
├── archetypes/          # Templates para novos conteúdos
├── assets/              # Assets do site
├── content/             # Conteúdo do site
│   ├── about.md         # Página Sobre
│   ├── pypi-packages.md # Página de pacotes PyPI
│   └── vscode-plugins.md # Página de plugins VSCode
├── data/                # Arquivos de dados
├── i18n/                # Arquivos de internacionalização
├── layouts/             # Overrides de templates do tema
│   └── partials/
│       └── footer.html  # Footer customizado
├── static/              # Arquivos estáticos
├── themes/              # Temas Hugo
│   └── PaperMod/        # Tema PaperMod
├── hugo.toml            # Configuração do Hugo
└── public/              # Arquivos gerados (não versionado)
```

## ⚙️ Configuração

As principais configurações estão no arquivo `hugo.toml`:

- **Base URL**: Configurado para produção e desenvolvimento
- **Idioma**: Português (pt-br)
- **Tema**: PaperMod
- **Social Icons**: GitHub e LinkedIn configurados
- **Home Info**: Conteúdo da página inicial

## 📝 Adicionando Conteúdo

### Criar uma nova página:

```bash
hugo new nome-da-pagina.md
```

### Criar um novo post:

```bash
hugo new posts/meu-post.md
```

## 🎨 Personalizações

### Footer

O footer foi customizado para remover o texto "Powered by". O arquivo está em `layouts/partials/footer.html`.

### Social Icons

Os ícones sociais (GitHub e LinkedIn) estão configurados em `hugo.toml` e aparecem na página inicial e no perfil.

## 📄 Páginas Disponíveis

- **Home** - Página inicial com apresentação
- **Sobre** - Informações profissionais e contato
- **PyPI Packages** - Lista de pacotes Python publicados
- **VSCode Plugins** - Lista de plugins do VSCode

## 🌐 Deploy

Para fazer deploy, gere os arquivos estáticos:

```bash
hugo
```

E então faça upload do conteúdo do diretório `public/` para seu servidor ou serviço de hospedagem.

### Deploy no GitHub Pages

1. Gere os arquivos estáticos:
```bash
hugo
```

2. Faça commit e push do diretório `public/` para a branch `gh-pages` ou configure GitHub Actions para deploy automático.

## 📚 Recursos

- [Documentação do Hugo](https://gohugo.io/documentation/)
- [Documentação do PaperMod](https://github.com/adityatelange/hugo-PaperMod/wiki)
- [Hugo PaperMod Demo](https://adityatelange.github.io/hugo-PaperMod/)

## 📝 Licença

Este projeto é pessoal. O tema PaperMod possui sua própria licença.

## 👤 Autor

**Silas Vasconcelos**

- GitHub: [@silasvasconcelos](https://github.com/silasvasconcelos)
- LinkedIn: [silasvasconcelos](https://linkedin.com/in/silasvasconcelos)
- Website: [silasvasconcelos.com](https://silasvasconcelos.com)
