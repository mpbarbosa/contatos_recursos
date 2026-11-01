---
nome: "Entire"
url: "https://entire.com/"
categoria: "Desenvolvimento / Plataforma de código"
tags: [git, forge, agentes-de-ia, code-review, ci, devtools]
status: "lista-de-espera"
modelo: "freemium"
cadastrado_em: "2026-11-01"
revisado_em: "2026-11-01"
---

# Entire

> "The Git forge for agent-human collaboration."

## Resumo

Plataforma de hospedagem de código (Git forge) desenhada para times em que
agentes de IA escrevem boa parte do código. Além dos commits, a Entire guarda a
**intenção** por trás de cada mudança — prompts, decisões e sessões de agentes —
ligada ao histórico do repositório.

A tese da empresa é que o fluxo baseado em pull request não escala quando
agentes geram código mais rápido do que humanos conseguem revisar.

## O que faz

Hospeda repositórios Git e, em paralelo, indexa o contexto que produziu o
código: prompts, traços de raciocínio, chamadas de ferramenta e transcrições de
sessão. Isso permite rastrear *por que* um trecho de código é como é, não apenas
*quem* o escreveu.

A arquitetura descrita publicamente tem três partes: um banco de dados
compatível com Git, uma camada de raciocínio semântico para coordenar vários
agentes, e uma interface de interação agente–humano.

## Para quem é

Times de engenharia que já usam agentes de codificação em volume e precisam de
governança, auditoria e revisão sobre código gerado por IA.

## Recursos principais

| Recurso | Descrição |
| --- | --- |
| **Code Hosting** | Hospedagem Git-compatível em rede distribuída, com repositórios em várias regiões. |
| **Trails** | Conduz o trabalho da ideia ao merge, substituindo o pull request tradicional; inclui revisão por agentes e evals. |
| **Session Storage / Entire CLI** | Captura sessões de agentes no terminal e as vincula aos commits. |
| **Checkpoints** | Primeiro produto lançado (open source): versiona prompts, raciocínio e artefatos de decisão junto aos commits. |
| **Continuous Memory** | Grafo pesquisável de repositório, prompts e chamadas de ferramenta, usado para dar contexto aos agentes. |
| **Agentic Search** | Busca unificada em código, commits e sessões. |
| **Continuous Integration** | Integração com provedores de CI: builds e testes rodam quando agentes dão push. |
| **Secret protection** | Detecta e redige segredos antes do armazenamento. |

## Preços

Não divulgados no site (consulta em 2026-11-01). O CLI e o benchmark
`forgemark` são open source; o acesso a entire.com é por convite.

## Contato e links

- Site: <https://entire.com/>
- Login: <https://entire.com/login>
- Acesso antecipado ("Join the rebellion"): <https://entire.com/rebellion>
- `forgemark` (benchmark open source): repositório no GitHub, linkado na home

O site não publica e-mail, endereço ou perfis de redes sociais.

## Empresa

- Fundada por **Thomas Dohmke**, ex-CEO do GitHub (saiu do GitHub em agosto de 2025).
- Lançada publicamente em **10 de fevereiro de 2026**.
- Seed de **US$ 60 milhões** a uma avaliação de US$ 300 milhões — segundo a
  Felicis (líder da rodada), o maior seed já feito por uma startup de devtools.
  Participaram Madrona, M12 (braço de venture da Microsoft) e Basis Set.
- Equipe pequena e remota (uma fonte cita ~15 pessoas; não confirmado).

## Observações

- **Status de acesso**: não há plano autosserviço aberto; é preciso entrar na
  lista de acesso antecipado em `/rebellion`.
- **Ponto de atenção**: o modelo depende de enviar prompts e transcrições de
  sessões para a plataforma. Vale avaliar a política de retenção e o alcance da
  redação de segredos antes de usar com código proprietário.
- **Avaliar depois**: se os preços e a disponibilidade geral forem publicados,
  revisar este cadastro.

## Fontes

- [entire.com](https://entire.com/) — home e /rebellion (consultados em 2026-11-01)
- [TechCrunch — Former GitHub CEO raises record $60M dev tool seed round](https://techcrunch.com/2026/02/10/former-github-ceo-raises-record-60m-dev-tool-seed-round-at-300m-valuation/)
- [Bloomberg — Former GitHub CEO Thomas Dohmke Raises $60 Million for New Startup](https://www.bloomberg.com/news/articles/2026-02-10/former-github-ceo-thomas-dohmke-raises-60-million-for-new-startup)
- [Redmond Channel Partner — Ex-GitHub CEO Thomas Dohmke Unveils Entire](https://rcpmag.com/articles/2026/02/12/ex-github-ceo-thomas-dohmke-unveils-entire.aspx)
- [implicator.ai — Dohmke Launches Entire With Record $60M Seed](https://www.implicator.ai/former-github-ceo-thomas-dohmke-raises-record-60m-for-new-startup-entire-2/)
