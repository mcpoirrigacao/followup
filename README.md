# Follow-up Semanal · MCPO

**Acesso:** https://mcpoirrigacao.github.io/followup/

Acompanhamento semanal em que cada equipe lança os próprios dados (semana de segunda a domingo).

## Como funciona
- Login com a conta Microsoft da MAQCAMPO (mesmo registro de app do Azure dos outros apps).
- Dados gravados na pasta **FollowUP** do SharePoint MCPOIRRIGACAO: `followup_dados.json` (equipes, campos e lançamentos) e `followup_acesso.json` (administradores e visualizadores).
- **Peças** e **Assistência Técnica** são lidas automaticamente dos apps `pecas` (pasta *Pecas Varejo*) e `assistencia` (pasta *assistencia*), somadas por semana e por loja.

## Acesso
- **Administrador:** vê e edita tudo, gerencia equipes, campos e usuários.
- **Quem preenche (por equipe):** cadastrado em *Equipes & Campos*; vê e edita só a própria equipe.
- **Visualizador:** vê todas as equipes, sem editar.

## Abas
- **Painel:** visão geral da semana (status de preenchimento, indicadores, pendências) e detalhe por equipe com gráfico de evolução, ranking por linha e histórico (exporta CSV).
- **Lançamentos:** tabela da semana por equipe; salva sozinho.
- **Equipes & Campos (admin):** adicionar/retirar campos, linhas (vendedores, lojas, regionais), segmentos (ex.: FRIO/MORNO/QUENTE), metas e quem preenche.
- **Parâmetros (admin):** usuários, fontes dos outros apps e importação do histórico da planilha *ACOMPANHAMENTO DE VENDAS.xlsx*.

Nenhum dado ou senha fica neste repositório.
