# Blog do Paghelp.me!

Este é o blog oficial do Paghelp.me!, onde compartilhamos novidades sobre PIX, dicas de uso do aplicativo e informações importantes sobre pagamentos instantâneos.

## Estrutura do Blog

```
blog/
├── index.html              # Página principal do blog (lista de posts)
├── posts/                  # Diretório com os posts individuais
│   ├── post-template.html  # Template padrão para novos posts
│   └── welcome-to-blog.html # Post de exemplo
└── README.md              # Este arquivo
```

## Como Adicionar um Novo Post

### 1. Copie o Template
Faça uma cópia do arquivo `posts/post-template.html` e renomeie com o slug do seu post:

```bash
cp posts/post-template.html posts/meu-novo-post.html
```

### 2. Edite o Conteúdo do Post
Abra o arquivo copiado e substitua todos os campos marcados com `[COLCHETES]`:

#### Meta Tags (na seção `<head>`):
- `[DESCRIÇÃO DO POST]` - Descrição de até 160 caracteres para SEO
- `[PALAVRAS-CHAVE ESPECÍFICAS DO POST]` - Palavras-chave separadas por vírgula
- `[TÍTULO DO POST]` - Título que aparecerá na aba do navegador

#### Conteúdo do Post:
- `[TÍTULO DO POST]` - Título principal do post
- `[YYYY-MM-DD]` - Data no formato ISO (ex: 2024-01-15)
- `[DD] de [MÊS], [YYYY]` - Data formatada em português (ex: 15 de Janeiro, 2024)
- `[NOME DO AUTOR]` - Nome do autor do post
- `[PARÁGRAFO INTRODUTÓRIO]` - Resumo destacado do post
- `[CONTEÚDO DO POST]` - Corpo principal do post
- `[SUBTÍTULO DA SEÇÃO]` - Subtítulos das seções
- `[CATEGORIA DO POST]` - Categoria (ex: Novidades PIX, Dicas do App, Tutoriais)

### 3. Adicione o Post à Lista do Blog
Edite o arquivo `index.html` e adicione um novo cartão de post na seção "Últimas Postagens". Use o template comentado como referência:

```html
<article class="card mb-4" style="background-color: #005489;">
    <div class="card-body text-white">
        <h3 class="card-title">
            <a href="posts/meu-novo-post.html" class="text-white text-decoration-none">Título do Meu Post</a>
        </h3>
        <p class="text-muted small mb-2">
            <time datetime="2024-01-15">15 de Janeiro, 2024</time>
        </p>
        <p class="card-text">Resumo breve do post que aparecerá na listagem...</p>
        <a href="posts/meu-novo-post.html" class="btn btn-light">Ler mais</a>
    </div>
</article>
```

## Diretrizes de Conteúdo

### Temas Sugeridos:
- Novidades sobre PIX no Brasil
- Tutoriais de uso do Paghelp.me!
- Dicas de segurança em pagamentos digitais
- Atualizações e novas funcionalidades do app
- Educação financeira relacionada ao PIX

### Padrões de Escrita:
- Use linguagem clara e acessível
- Mantenha o foco no público brasileiro
- Inclua chamadas para ação (download do app, etc.)
- Use títulos descritivos e envolventes
- Mantenha consistência com o tom da marca

### SEO e Acessibilidade:
- Sempre preencha as meta descriptions
- Use títulos hierárquicos (h1, h2, h3)
- Inclua atributos alt em imagens
- Use links descritivos
- Mantenha URLs amigáveis (slug do post)

## Estilo Visual

O blog segue o mesmo padrão visual do site principal:
- **Cor primária:** #16a085 (verde agua)
- **Cor secundária:** #005489 (azul escuro)
- **Fonte:** Bootstrap padrão
- **Layout:** Responsivo usando Bootstrap 5.0.0-beta2

## Navegação

- Link para voltar ao blog principal em cada post
- Navegação entre posts (quando aplicável)
- Breadcrumb visual através da navegação superior
- Sidebar com informações sobre o blog e link para download do app

## Dicas Técnicas

1. **URLs dos posts:** Use formato `posts/slug-do-post.html`
2. **Datas:** Sempre inclua o atributo `datetime` nas tags `<time>`
3. **Links:** Use caminhos relativos para navegação interna
4. **Imagens:** Se precisar de imagens, adicione na pasta `../src/img/blog/`
5. **Analytics:** Todos os posts já incluem o código do Google Analytics

## Exemplo de Slug

Para um post chamado "Como Criar uma Chave PIX no Paghelp.me!", o slug seria:
`como-criar-chave-pix-paghelp-me.html`

Regras para slugs:
- Tudo em minúsculas
- Substitua espaços por hífens
- Remova acentos e caracteres especiais
- Mantenha apenas letras, números e hífens