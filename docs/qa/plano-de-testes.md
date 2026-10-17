Plano de Testes — VISA Digital

1. Identificação do projeto

- Projeto: VISA Digital
- Tipo: Protótipo web demonstrativo
- Área: Gestão da Vigilância Sanitária
- Responsável pela documentação de QA: Bruno Castro
- Tipo de teste: Testes funcionais manuais
- Status: Planejamento inicial

2. Objetivo

Definir a estratégia para validar manualmente as funcionalidades demonstrativas do VISA Digital, verificando se os comportamentos observados correspondem aos resultados esperados.

3. Escopo dos testes

Serão priorizadas as seguintes áreas:

- Visão geral e indicadores.
- Cadastro, consulta, edição e exclusão de estabelecimentos.
- Cadastro, consulta e exportação de processos sanitários.
- Planejamento, consulta e atualização de inspeções.
- Relatórios, filtros e exportação.
- Dossiê digital do estabelecimento.
- Providências, prazos e central de alertas.
- Backup e restauração, conforme os recursos disponíveis no protótipo.

A inclusão de cada funcionalidade no escopo não significa que ela já tenha sido testada ou aprovada.

4. Ambiente de teste

- Aplicação: VISA Digital.
- Execução: arquivo `index.html` aberto em navegador.
- Navegador: Google Chrome.
- Armazenamento: local no navegador.
- Dados: exclusivamente fictícios.
- Tipo de execução: manual.

A versão exata do navegador, a data de execução e outros detalhes do ambiente deverão ser registrados durante os testes.

5. Tipos de teste previstos

- Testes funcionais: validar as funções disponíveis.
- Testes positivos: verificar operações com dados válidos.
- Testes negativos: verificar o tratamento de dados ausentes ou inválidos.
- Testes de consulta e filtros: conferir os registros apresentados.
- Testes de exportação: verificar arquivos CSV e impressão ou salvamento em PDF, quando disponíveis.
- Testes de persistência: verificar o comportamento dos dados após atualizar ou reabrir a aplicação.
- Testes de consistência: comparar indicadores, listagens e relatórios relacionados.

6. Critérios de entrada

- Aplicação disponível para execução.
- Ambiente demonstrativo acessível.
- Dados fictícios preparados.
- Funcionalidade sob teste identificada.
- Caso de teste documentado com passos e resultado esperado.

7. Critérios de aprovação

Um caso de teste será considerado aprovado quando o resultado observado corresponder ao resultado esperado definido no caso.

Quando houver divergência, erro ou impossibilidade de concluir a execução, o resultado deverá ser registrado para análise.

8. Registro dos resultados

Cada execução deverá registrar:

- Identificador do caso de teste.
- Data da execução.
- Resultado: Aprovado, Reprovado ou Bloqueado.
- Resultado observado.
- Evidência, quando aplicável.
- Descrição do defeito, quando identificado.

9. Limitações e cuidados

O VISA Digital é um protótipo demonstrativo. Os dados são armazenados localmente no navegador e não devem ser tratados como registros oficiais.

Não serão utilizados dados pessoais, sigilosos ou reais. Os testes não devem ser interpretados como certificação de segurança, conformidade legal ou homologação administrativa.

10. Status atual

Planejamento inicial. Os testes ainda precisam ser executados e seus resultados documentados.

O plano poderá ser atualizado conforme o comportamento real das funcionalidades for verificado.
