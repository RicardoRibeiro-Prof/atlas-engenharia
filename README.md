# Atlas Engenharia

Projeto demonstrativo de escritório de engenharia criado para portfólio, com layout técnico, páginas estáticas pré-renderizadas, SEO por rota e publicação no GitHub Pages.

## Identidade

- grafite, laranja queimado, branco e cinza concreto;
- layout técnico e arquitetônico;
- imagens reais de obras, projetos e profissionais;
- serviços em painéis modulares;
- portfólio de projetos em destaque;
- páginas individuais de serviços e artigos;
- modo demonstração com `noindex, nofollow`;
- auditoria automática do build;
- botão de WhatsApp e menu responsivo.

## Executar localmente

```bash
npm ci
npm run build
```

A pasta final é `dist/`.

## Publicação

O workflow `.github/workflows/deploy-pages.yml` publica exclusivamente a pasta `dist` no GitHub Pages.

O GitHub Pages já foi configurado para usar **GitHub Actions**. Este commit dispara a primeira publicação oficial do projeto.

URL esperada:

`https://ricardoribeiro-prof.github.io/atlas-engenharia/`

## Aviso

Empresa, profissionais, projetos, registros e contatos são fictícios. Antes de uso real, substitua todos os dados demonstrativos e revise a política de privacidade.
