# Andromeda Pass 5.0 para Claude Code

Este pacote organiza o Andromeda Pass como um projeto utilizável no Claude Code.

## Estrutura

```text
andromeda-pass-claude-code/
├── CLAUDE.md
├── README.md
└── knowledge/
    ├── 01_LINGUAGEM_NATIVA_ANTI_REATANCIA_5.0.md
    ├── 02_VOCABULARIO_NAO_PERMITIDO_SUBSTITUICOES_5.0.md
    ├── 03_REGRAS_POR_FORMATO_5.0.md
    ├── 04_EXEMPLOS_DE_HOOKS_BONS_E_RUINS_5.0.md
    ├── 05_EXEMPLOS_DE_CTA_ORGANICO_5.0.md
    ├── 06_DIRECAO_VISUAL_POR_NICHO_PADROES_DE_IMAGEM_PREMIUM_5.0.md
    ├── 07_O_QUE_EVITAR_EM_IMAGEM_5.0.md
    └── 08_GUIA_DE_SAIDA_SUPER_PROMPT_5.0.md
```

## Instalação

1. Descompacte a pasta em um diretório próprio.
2. Abra o terminal nessa pasta.
3. Inicie o Claude Code a partir da raiz do projeto.
4. Mantenha `CLAUDE.md` na raiz e a pasta `knowledge/` no mesmo nível.
5. Comece uma nova conversa e peça para executar o fluxo do Andromeda Pass.

## Como funciona

`CLAUDE.md` contém as regras operacionais: coleta de input, definição do objetivo, diagnóstico, aprovação, criação dos exatamente nove criativos, QA e Super Prompts.

A pasta `knowledge/` contém a base especializada. O `CLAUDE.md` instrui o agente a consultar esses arquivos conforme a etapa.

## Teste recomendado

Depois de abrir o projeto no Claude Code, envie:

> Inicie uma nova execução do Andromeda Pass 5.0 e siga o CLAUDE.md e a base em knowledge/.

O comportamento esperado é iniciar pela escolha entre responder perguntas ou fornecer material existente. Ele não deve pular diretamente para os nove criativos.

## Atualizações futuras

Para alterar o comportamento central, edite `CLAUDE.md`.

Para alterar linguagem, hooks, CTAs, formatos, direção visual ou Super Prompts, atualize o documento correspondente em `knowledge/`.

## Observação

Este pacote foi montado a partir das especificações fornecidas para a versão Claude Code e dos oito documentos de conhecimento fornecidos pelo usuário. Ele não depende de arquivos externos além dos incluídos nesta pasta.
