# Logar no Varstation

Usuários: alunoNN@einstein.br
Senha:PergunteAoProfessor

https://app.varstation.com/

# Cadastro de Paciente
Após realizar o logon na plataforma, clique em "Pacientes" na aba superior da página para acessar as opções de registro.
As opções para cadastro dos dados pessoais dos pacientes são:
- Nome
- Gênero
- Número de Registro
- Data de nascimento
- Documento de identidade
- Opção para outros documentos ou registros

# Criando um painel de genes para análise
Criar um painel de genes com os genes: BRCA1 e BRCA2.
Para criar um novo painel, basta especificar o nome ao novo painel e inserir os genes de interesse nos campos designados em Detalhamento.
Após o preenchimento dos dados, clique em Salvar para criação do Painel.

Os painéis de genes podem ser utilizados como um filtro tanto durante a análise das variantes, como na hora de montar um pipeline específico. O Varstation disponibiliza alguns painéis públicos em seu banco de dados e para acessá-los, basta escolher entre as opções disponíveis no menu ao lado esquerdo da página ou ainda pesquisar os painéis criados no campo de busca.

# Criando um filtro de análise
Os filtros serão utilizados para excluir variantes que não interessam na análise, como por exemplo, as de baixa cobertura, com strand bias ou, ainda, filtrar falsos positivos. Podem ser utilizados filtros públicos já disponíveis no banco de dados do próprio Varstation (localizados ao lado esquerdo da página) ou criar um novo personalizado. Para isso, basta preencher o nome do novo filtro e selecionar a(s) referência(s), operador e valor de referência que se deseja no filtro. Deve-se escolher também se ele se trata de um filtro padrão (que deleta as variantes que não se adequam à condição) ou um filtro suave (apenas marca as variantes que não se adequam à condição, sem deletá-las).

# Envio (upload) de arquivos para o Varstation
Os formatos de arquivos suportados pela plataforma são .FASTQ, .BAM e .VCF.
Na página inicial, arraste os arquivos desejados até a área demarcada na parte central da página ou clique em selecionar arquivos. Escolha os arquivos desejados no browser de arquivos e então clique em "abrir". Caso os arquivos tenham sido arrastados, clique em "Continuar".

# Analisando as métricas de sequenciamento
Quando o processamento da rotina for finalizado, ela ficará com o status, indicando que está pronta para ser analisada. Para iniciar a análise das métricas de qualidade, clique na rotina desejada. A janela mostrará dados da corrida e do processamento. Para visualizar as métricas de qualidade, clique em MÉTRICAS.
Uma nova janela se abrirá com dados contendo nome da amostra, cobertura média, uniformidade, cobertura média no alvo, valor de phred score (Q) para avaliar o mapeamento, cobertura UMI (quando houver) e o status final. Quando uma ou mais métricas não passarem no controle de qualidade, ela ficará vermelha e caso necessário a amostra poderá ser rejeitada da análise. Para isso, basta clicar no botão vermelho localizado do lado direito da amostra com métricas reprovadas.

# Ferramentas de análise e classificação
Para iniciar a análise das variantes, utilize a aba denominada VARIANTES. Para consultar as variantes chamadas, bem como as informações relevantes que foram associadas, continue navegando nessa aba. Para iniciar o processo de análise, clique em START.
