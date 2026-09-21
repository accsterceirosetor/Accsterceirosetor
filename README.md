# ACCS Terceiro Setor

Site institucional da **ACCS Gestão e Prestação de Contas para o Terceiro Setor** (UFBA): divulga o componente curricular, publicações dos estudantes e editais de atendimento a organizações da sociedade civil.

## Stack

- **Hugo** — gerador de site estático, com tema custom `themes/accs` que preserva o design original
- **Decap CMS** — gerenciamento de conteúdo (publicações e editais) em `/admin/`
- **Netlify** — build, deploy e autenticação (Netlify Identity + Git Gateway)
- GitHub como backend do conteúdo