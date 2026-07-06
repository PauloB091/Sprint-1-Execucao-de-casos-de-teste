## Checklists de Execucao

### Checklist de Pre-execucao

-   Ambiente de teste devidamente configurado
-   Versao do sistema validada e disponivel para teste
-   Casos de teste revisados e aprovados
-   Dados de teste necessarios disponiveis
-   Permissoes de acesso liberadas para os testadores

### Checklist Durante a Execucao

-   Executar cada caso de teste conforme o roteiro definido
-   Registrar o resultado de cada passo executado
-   Coletar evidencias em caso de falhas (screenshots ou logs)
-   Reproduzir falhas identificadas para confirmar o comportamento
-   Anotar observacoes relevantes sobre o comportamento do sistema

### Checklist de Pos-execucao

-   Atualizar o status final de todos os casos de teste
-   Abrir relatorios de bugs para todas as falhas encontradas
-   Consolidar as metricas de execucao do ciclo
-   Registrar licoes aprendidas durante o processo
-   Encerrar formalmente o ciclo de teste

## Casos de Teste

A tabela abaixo apresenta a estrutura padrao utilizada para a escrita dos
casos de teste.

| ID | Titulo | Pre-condicoes | Passos | Resultado esperado | Resultado real | Status | Evidencias |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| CT-001 | Login com sucesso | Usuario cadastrado e ativo | 1. Acessar login; 2. Inserir credenciais; 3. Clicar em entrar | Acesso concedido a area logada | Usuario redirecionado para a home | Passou | link-para-imagem.png |

## Relatorios de Bug

Falhas identificadas devem ser registradas seguindo o padrao abaixo.

| ID | Titulo | Ambiente | Pre-condicoes | Passos para reproduzir | Resultado esperado | Resultado real | Severidade | Prioridade | Evidencias | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| BUG-001 | Erro ao salvar perfil | Homologacao | Usuario logado | 1. Editar perfil; 2. Clicar em salvar | Dados salvos com sucesso | Erro 500 ao clicar em salvar | Alta | Alta | log-erro.txt | Aberto |

## Boas Praticas

-   Manter a objetividade na descricao dos passos de teste
-   Garantir que as evidencias sejam claras e legiveis
-   Descrever os bugs de forma que qualquer membro da equipe consiga
    reproduzi-los
-   Atualizar o status da execucao em tempo real para visibilidade do
    projeto
-   Revisar os dados de teste antes de iniciar a execucao para evitar
    bloqueios desnecessarios
