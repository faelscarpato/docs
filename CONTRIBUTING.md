# Contribuindo com CapyUniverse Docs

## Antes de editar

Identifique se a alteração é:

- documentação da plataforma;
- documentação de agente;
- documentação de projeto filho;
- padrão técnico;
- governança;
- template ou glossário.

## Como adicionar uma página

1. Crie o arquivo `.mdx` na pasta correta.
2. Adicione frontmatter com `title` e `description`.
3. Inclua a página no `docs.json` se ela for oficial.
4. Rode validação local.
5. Verifique se não há conteúdo antigo do template.

## Como escrever

- Use frases diretas.
- Liste limitações sem esconder problemas.
- Não prometa funcionalidades que ainda não existem.
- Use tabelas para comparação, risco e roadmap.
- Registre fonte do projeto quando possível.

## Checklist de PR

- [ ] `docs.json` válido.
- [ ] Links testados.
- [ ] Nenhum segredo no conteúdo.
- [ ] Nenhum conteúdo do starter Mintlify.
- [ ] Página segue padrão de projeto/agente quando aplicável.
