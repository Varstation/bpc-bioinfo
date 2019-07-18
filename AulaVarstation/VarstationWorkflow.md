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

