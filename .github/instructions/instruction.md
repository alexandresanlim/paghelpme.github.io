# Instruções do Projeto Paghelp.me

Este documento contém instruções para desenvolvimento e contribuição no projeto Paghelp.me - um aplicativo para gerenciamento de chaves Pix.

## Sobre o Projeto

O Paghelp.me é uma landing page para um aplicativo mobile que permite:
- Gerenciar todas as suas chaves Pix em um único aplicativo
- Criar cobranças mesmo offline
- Fazer backup sem necessidade de login e armazenamento
- E muito mais funcionalidades relacionadas ao sistema Pix

## Estrutura do Projeto

```
/
├── index.html          # Página principal da landing page
├── src/                # Recursos do projeto
│   └── img/           # Imagens e recursos visuais
├── privacy/           # Páginas de políticas de privacidade
├── README.md          # Documentação principal
└── .github/           # Arquivos de configuração do GitHub
    └── instructions/  # Instruções e documentação
```

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **Bootstrap 5**: Framework CSS para responsividade
- **Google Analytics**: Acompanhamento de métricas
- **GitHub Pages**: Hospedagem da landing page

## Como Contribuir

### 1. Modificando o Conteúdo

Para alterar o conteúdo da landing page:
1. Edite o arquivo `index.html`
2. Mantenha a estrutura Bootstrap existente
3. Teste a responsividade em diferentes dispositivos

### 2. Adicionando Imagens

Para adicionar novas imagens:
1. Coloque os arquivos na pasta `src/img/`
2. Use formatos otimizados (PNG, JPG, WebP)
3. Mantenha nomes descritivos para os arquivos

### 3. Atualizando Estilos

- O projeto usa Bootstrap 5 via CDN
- Estilos customizados devem ser adicionados inline ou em arquivo CSS separado
- Mantenha a consistência visual com o design atual

## Diretrizes de Desenvolvimento

### Responsividade
- Teste em dispositivos mobile, tablet e desktop
- Use as classes do Bootstrap para garantir responsividade
- Priorize a experiência mobile (mobile-first)

### Performance
- Otimize imagens antes de adicionar ao projeto
- Mantenha o código limpo e organizado
- Use CDNs para bibliotecas externas

### SEO
- Mantenha as meta tags atualizadas
- Use títulos e descrições relevantes
- Implemente structured data quando apropriado

## Deployment

O projeto é automaticamente deployado via GitHub Pages quando mudanças são feitas na branch principal.

## Contato

Para dúvidas ou sugestões relacionadas ao projeto, entre em contato através dos canais oficiais do Paghelp.me.

---

**Nota**: Este é um projeto de landing page para o aplicativo Paghelp.me. Para questões relacionadas ao aplicativo em si, consulte a documentação específica do app.