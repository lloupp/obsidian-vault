---
tags: [vault/index]
aliases: [Mapa do Vault, Vault]
created: 2026-07-13
---
# Obsidian Vault

Meu vault pessoal para anotações e conhecimento.

## Mapa (MOC)
- Captura rápida: [[Inbox]]
- Projetos: `01 - Projects/`
- Conhecimento: `02 - Knowledge/` → Programming, Termux, Pi
- Modelo de nota: [[Template de Nota]]

## Estrutura

```
├── 00 - Inbox/
├── 01 - Projects/
├── 02 - Knowledge/
│   ├── Programming/
│   ├── Termux/
│   └── Pi/
├── Templates/
└── README.md
```

## Como usar

1. Abra este diretório no Obsidian
2. Configurações em `.obsidian/` (opcional)

## Sincronização

Repositório Git para versionamento e sincronização entre dispositivos.

Não versionar:
- `.trash/`
- `~temp/`

## Convenções (boas práticas)
- Cada nota tem frontmatter com `tags`, `aliases` e `created` (YAML entre `---`).
- Use `[[wikilinks]]` para conectar notas; `![[Nota]]` para embeds.
- Tags em kebab-case e aninhadas: `#area/subarea` (no frontmatter como lista).
- Nomes de arquivo sem os caracteres inválidos em links: `# | ^ : %% [[ ]]`.
- Notas atômicas: uma ideia por nota; conecte, não acumule.
