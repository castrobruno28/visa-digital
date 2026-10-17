Relatório de Melhorias — VISA Digital

1. Identificação

- Projeto: VISA Digital
- Tipo de documento: Relatório de melhorias identificadas durante testes manuais
- Responsável pelos testes: Bruno Castro
- Data da execução: 17/10/2026
- Origem: Execução dos casos de teste CT-007 e CT-008
- Status: Melhorias identificadas — requisitos pendentes de confirmação

2. Objetivo

Documentar oportunidades de melhoria observadas durante a execução dos testes manuais do protótipo VISA Digital, com foco na usabilidade dos filtros de inspeção e na flexibilidade dos relatórios.

As observações registradas neste documento não são consideradas defeitos confirmados, pois ainda é necessário verificar se os comportamentos identificados contrariam os requisitos definidos para o projeto.

3. Melhoria M-001 — Limpar filtro de inspeções

Identificação: M-001  
Módulo: Inspeções  
Origem: CT-007 — Filtrar inspeções  
Classificação: Melhoria de usabilidade  
Status: Pendente de avaliação

Descrição

Durante o teste, os filtros por situação retornaram os registros esperados. Entretanto, não foi identificada uma opção visível para limpar o filtro aplicado.

Resultado observado

A filtragem funcionou conforme esperado, mas não foi localizada uma opção específica para remover o filtro e retornar à visualização sem filtragem.

Impacto potencial

A ausência dessa opção pode dificultar a navegação e exigir que o usuário encontre outra maneira de voltar à visualização anterior.

Recomendação

Avaliar a inclusão de um botão ou controle “Limpar filtros”, permitindo retornar facilmente à listagem completa de inspeções.

Critério sugerido para validação

Após aplicar um filtro, o usuário deve conseguir limpar os critérios selecionados e visualizar novamente todos os registros disponíveis.

4. Melhoria M-002 — Selecionar técnico individual no relatório

Identificação: M-002  
Módulo: Relatórios  
Origem: CT-008 — Atualizar relatório por período  
Classificação: Melhoria funcional  
Status: Pendente de avaliação

Descrição

Durante o teste, foi observado que o relatório apresenta os dados de todos os técnicos para o período selecionado. Não foi identificada uma opção para selecionar um técnico específico.

Resultado observado

A atualização do relatório por período funcionou conforme observado. Entretanto, não foi localizada uma opção para filtrar os dados por técnico individual.

Impacto potencial

A ausência desse recurso pode limitar análises individuais de produtividade e dificultar a consulta de informações de um técnico específico.

Recomendação

Avaliar a inclusão de um filtro por técnico, permitindo selecionar um profissional e consultar os registros correspondentes ao período escolhido.

Critério sugerido para validação

Após selecionar um período e um técnico, o relatório deve apresentar somente os registros correspondentes aos critérios selecionados, conforme as regras que forem definidas para o sistema.

5. Resumo das melhorias

| ID | Módulo | Melhoria identificada | Origem | Status |
|---|---|---|---|---|
| M-001 | Inspeções | Opção para limpar filtros | CT-007 | Pendente de avaliação |
| M-002 | Relatórios | Filtro por técnico individual | CT-008 | Pendente de avaliação |

6. Considerações finais

As observações foram identificadas durante a execução dos testes manuais do protótipo VISA Digital.

As recomendações apresentadas têm como objetivo melhorar a experiência de uso e ampliar as possibilidades de consulta. Antes de implementar qualquer alteração, recomenda-se validar as necessidades com os responsáveis pelo projeto e confirmar os requisitos funcionais.

Este documento registra oportunidades de melhoria observadas durante os testes. Não representa uma confirmação de defeitos nem uma aprovação para uso institucional do protótipo.