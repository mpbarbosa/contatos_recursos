# contatos_recursos

Cadastro de contatos e recursos.

## Estrutura

```
contatos/            # um arquivo por contato
recursos/            # um arquivo por serviço, ferramenta ou recurso
templates/           # modelos para novos cadastros
```

Cada cadastro é um arquivo Markdown com frontmatter YAML, nomeado em
kebab-case (ex.: `recursos/entire.md`).

Campos do frontmatter de um recurso:

| Campo | Valores |
| --- | --- |
| `nome` | nome do serviço |
| `url` | endereço principal |
| `categoria` | área de uso |
| `tags` | lista de palavras-chave |
| `status` | `ativo`, `beta`, `lista-de-espera`, `descontinuado` |
| `modelo` | `gratuito`, `freemium`, `pago`, `open-source` |
| `cadastrado_em` | data do primeiro cadastro (AAAA-MM-DD) |
| `revisado_em` | data da última revisão (AAAA-MM-DD) |

Para adicionar um recurso, copie [templates/recurso.md](templates/recurso.md).

## Índice de recursos

| Recurso | Categoria | Status | Cadastro |
| --- | --- | --- | --- |
| [Entire](recursos/entire.md) | Desenvolvimento / Plataforma de código | lista-de-espera | 2026-11-01 |
