Casos de Teste — VISA Digital

1. Identificação

- Projeto: VISA Digital
- Tipo: Testes funcionais manuais
- Ambiente: Protótipo executado localmente no navegador
- Dados: Fictícios
- Status geral: Casos planejados; execução pendente

2. Convenções

- Aprovado: resultado observado corresponde ao esperado.
- Reprovado: resultado observado diverge do esperado.
- Bloqueado: não foi possível executar o teste.
- Não executado: teste ainda não realizado.

3. Casos de teste

CT-001 — Consultar o painel geral

Objetivo: verificar se o painel apresenta os indicadores e as atividades demonstrativas.

Pré-condições:
- Aplicação aberta.
- Acesso à tela Visão geral.

Passos:
1. Acessar a tela Visão geral.
2. Observar os cartões de indicadores.
3. Conferir as áreas de atividades recentes e produtividade.

Resultado esperado: o painel é exibido e apresenta os indicadores e as informações disponíveis no ambiente demonstrativo.

Resultado obtido: O painel geral foi consultado e o teste foi concluído com sucesso, conforme resultado informado na execução.

Status: Aprovado.

Observações: Nenhuma observação registrada.

---

CT-002 — Consultar estabelecimentos

Objetivo: verificar se os registros demonstrativos são exibidos.

Pré-condições:
- Aplicação aberta.
- Acesso ao módulo Estabelecimentos.

Passos:
1. Abrir Estabelecimentos.
2. Observar a listagem.
3. Conferir os campos de identificação, atividade, situação e documento.

Resultado esperado: a listagem é exibida com os registros disponíveis e suas informações correspondentes.

Resultado obtido: A listagem de estabelecimentos e suas informações foram exibidas conforme esperado.

Status: Aprovado.

Observações: Todas as informações da listagem foram exibidas.

---

CT-003 — Pesquisar estabelecimento

Objetivo: verificar a pesquisa por nome ou outro critério disponível.

Pré-condições:
- Módulo Estabelecimentos aberto.
- Existência de registros fictícios para consulta.

Passos:
1. Digitar o nome de um estabelecimento existente no campo de busca.
2. Observar os resultados.
3. Substituir a pesquisa por um nome que não exista.

Resultado esperado: a pesquisa apresenta os registros compatíveis com o termo digitado e trata adequadamente uma busca sem correspondências.

Resultado obtido: A pesquisa por um estabelecimento existente retornou o resultado esperado. A pesquisa por um nome inexistente também se comportou conforme esperado.

Status: Aprovado.

Observações: Os dois cenários funcionaram como esperado.

---

CT-004 — Validar campos obrigatórios de processo

Objetivo: verificar a validação do formulário de processos sanitários.

Pré-condições:
- Módulo Processos sanitários aberto.

Passos:
1. Deixar vazios os campos obrigatórios.
2. Acionar Salvar processo.
3. Observar as mensagens e o comportamento do formulário.

Resultado esperado: o sistema impede o salvamento de um registro inválido e informa os campos que precisam ser preenchidos.

Resultado obtido: O sistema impediu o salvamento do processo quando os campos obrigatórios não estavam preenchidos e exigiu o preenchimento de um campo.

Status: Aprovado.

Observações: O sistema impediu o salvamento e exigiu preenchimento de campo.

---

CT-005 — Cadastrar processo válido

Objetivo: verificar o cadastro de um processo com informações válidas.

Pré-condições:
- Módulo Processos sanitários aberto.
- Estabelecimento demonstrativo disponível.

Passos:
1. Informar um número de processo fictício e ainda não utilizado.
2. Selecionar um estabelecimento.
3. Informar a data de abertura.
4. Preencher os demais campos conforme as regras disponíveis.
5. Salvar o processo.
6. Consultar a listagem.

Resultado esperado: o processo é salvo e aparece na consulta com os dados informados.

Resultado obtido: O processo foi cadastrado com dados válidos e o funcionamento ocorreu conforme esperado.

Status: Aprovado.

Observações: Teste realizado com sucesso.

---

CT-006 — Consultar agenda de inspeções

Objetivo: verificar a apresentação dos registros de inspeção.

Pré-condições:
- Módulo Inspeções aberto.

Passos:
1. Acessar a agenda de inspeções.
2. Observar as datas, os estabelecimentos, os técnicos responsáveis e as situações.
3. Comparar as informações com os registros demonstrativos apresentados.

Resultado esperado: a agenda exibe os registros disponíveis e suas informações correspondentes.

Resultado obtido: A agenda de inspeções foi consultada e as informações foram exibidas conforme esperado.

Status: Aprovado.

Observações: Teste aprovado; funcionamento conforme esperado.

---

CT-007 — Filtrar inspeções

Objetivo: verificar o funcionamento dos filtros disponíveis.

Pré-condições:
- Módulo Inspeções aberto.
- Existência de inspeções com situações distintas.

Passos:
1. Selecionar uma situação no filtro.
2. Observar os registros exibidos.
3. Alterar o filtro para outra situação.
4. Comparar os resultados.

Resultado esperado: a listagem corresponde ao filtro selecionado.

Resultado obtido: Os filtros por situação retornaram os registros esperados. Não foi identificada uma opção específica para limpar o filtro.

Status: Aprovado com observação.

Observações: A filtragem funcionou corretamente, porém não há opção visível para limpar o filtro. Recomenda-se avaliar a inclusão dessa funcionalidade para melhorar a usabilidade.

---

CT-008 — Atualizar relatório por período

Objetivo: verificar a atualização dos indicadores conforme o período selecionado.

Pré-condições:
- Módulo Relatórios aberto.
- Existência de registros demonstrativos.

Passos:
1. Informar uma data inicial válida.
2. Informar uma data final válida.
3. Selecionar o técnico, quando aplicável.
4. Acionar Atualizar relatório.
5. Conferir os indicadores e o detalhamento.

Resultado esperado: o relatório é atualizado de acordo com os filtros selecionados e apresenta informações coerentes com os registros correspondentes.

Resultado obtido: O relatório apresenta os dados de todos os técnicos para o período selecionado. Não foi identificada uma opção para selecionar um técnico específico.

Status: Aprovado com observação.

Observações: A atualização do relatório por período funciona conforme observado, porém não há filtro para selecionar um técnico individualmente. Recomenda-se avaliar a inclusão desse recurso. A ausência do filtro será considerada uma limitação funcional a confirmar conforme os requisitos do projeto.

---

T-009 — Consultar dossiê digital

Objetivo: verificar a consulta integrada das informações de um estabelecimento.

Pré-condições:
- Módulo Dossiê digital aberto.
- Existência de estabelecimento demonstrativo.

Passos:
1. Selecionar um estabelecimento.
2. Conferir os indicadores de inspeções, documentos, providências e processos.
3. Examinar as seções detalhadas.

Resultado esperado: o dossiê apresenta as informações disponíveis para o estabelecimento selecionado, sem misturar registros de outros estabelecimentos.

Resultado obtido: O dossiê digital foi consultado e apresentou as informações do estabelecimento selecionado conforme esperado.

Status: Aprovado.

Observações: Teste realizado; sistema funcionou como esperado.

---

CT-010 — Exportar relatório CSV

Objetivo: verificar a exportação de dados do módulo de relatórios.

Pré-condições:
- Módulo Relatórios aberto.
- Registros demonstrativos disponíveis.

Passos:
1. Acionar Exportar CSV.
2. Localizar o arquivo gerado.
3. Abrir o arquivo em um editor de texto ou aplicativo de planilha.
4. Conferir cabeçalhos e registros exportados.

Resultado esperado: o arquivo é gerado e contém os dados correspondentes ao relatório exportado, com campos identificáveis.

Resultado obtido: A exportação do relatório em CSV foi realizada e o teste funcionou conforme esperado.

Status: Aprovado.

Observações: Teste realizado com sucesso, conforme resultado informado.

4. Registro das execuções dos testes

| ID | Data | Resultado | Evidência | Observações |
|---|---|---|---|---|
| CT-001 | 17/10/2026 | Aprovado | Captura 01 — Painel geral | Nenhuma observação registrada |
| CT-002 | 17/10/2026 | Aprovado | Captura 02 — Estabelecimentos | Todas as informações da listagem foram exibidas |
| CT-003 | 17/10/2026 | Aprovado | Módulo Estabelecimentos | Os dois cenários funcionaram como esperado |
| CT-004 | 17/10/2026 | Aprovado | Módulo Processos sanitários | O sistema impediu o salvamento e exigiu preenchimento de campo |
 CT-005 | 17/10/2026 | Aprovado | Módulo Processos sanitários | Cadastro realizado e funcionando como esperado
| CT-006 | 17/10/2026 | Aprovado | Módulo Inspeções | Informações exibidas e funcionamento conforme esperado |
| CT-007 | 17/10/2026 | Aprovado com observação | Módulo Inspeções | Filtros funcionam; não há opção visível para limpar o filtro |
| CT-008 | 17/10/2026 | Aprovado com observação | Módulo Relatórios | Relatório por período funciona; não há seleção individual de técnico |
| CT-009 | 17/10/2026 | Aprovado | Módulo Dossiê digital | Sistema funcionou conforme esperado |
| CT-010 | 17/10/2026 | Aprovado | Módulo Relatórios — Exportação CSV | Teste realizado e aprovado |

5. Observação

Os resultados esperados são critérios de validação definidos para os testes. Nenhum caso deve ser marcado como aprovado ou reprovado antes da execução e do registro do resultado observado.
