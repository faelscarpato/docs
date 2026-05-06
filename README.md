# CapyUniverse Docs

Documentação oficial do ecossistema **CapyUniverse**: plataforma-mãe para ferramentas, agentes IA e projetos filhos como ValeRepor, Bicou, CapyMind, BuskaCEP e Sentinela Pedreira.

## Objetivo

Transformar o antigo starter Mintlify em uma documentação real para organizar:

- visão geral do CapyUniverse;
- arquitetura da plataforma;
- padrão de CapyTools;
- agentes especializados;
- projetos filhos;
- governança, segurança e roadmap;
- templates de documentação.

## Como rodar localmente

Instale a CLI do Mintlify:

```bash
npm i -g mint
```

Rode a documentação:

```bash
mint dev
```

Acesse:

```bash
http://localhost:3000
```

## Estrutura

```txt
capyuniverse-docs/
├── docs.json
├── index.mdx
├── quickstart.mdx
├── platform/
├── agents/
├── projects/
├── development/
├── governance/
├── reference/
├── logo/
└── .github/workflows/
```

## Projetos documentados

- CapyUniverse Core
- ValeRepor
- Bicou
- CapyMind
- BuskaCEP
- Sentinela Pedreira

## Checklist antes de publicar

- [ ] Revisar nome, links e branding.
- [ ] Confirmar se todos os projetos filhos continuam atualizados.
- [ ] Rodar validação local.
- [ ] Remover conteúdos antigos ou temporários.
- [ ] Publicar no repositório definitivo.

## Links úteis

- CapyUniverse: https://github.com/faelscarpato/capyuniverse
- Demo: https://faelscarpato.github.io/capyuniverse/
- Perfil GitHub: https://github.com/faelscarpato
