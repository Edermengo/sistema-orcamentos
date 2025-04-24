Estrutura do Sistema de Orçamentos em Excel
Planilhas Necessárias

    Instruções
        Documentação do sistema
        Guia rápido de uso
        Informações de versão

    Configurações
        BDI: 25%
        Encargos Sociais: 112,5%
        Dados da empresa
        Configurações gerais

    Insumos
        Lista completa de insumos
        Colunas: Código, Descrição, Unidade, Preço Unitário, Fonte

    Composições
        Lista de composições de serviços
        Detalhamento de composições com insumos
        Cálculo automático de preços

    Obras
        Orçamento hierárquico
        Estrutura de níveis (1, 1.1, 1.1.1)
        Totalização automática
        Cálculo com BDI

    Relatórios
        Curva ABC
        Resumos por etapa
        Gráficos de distribuição
Assistente de Programação

Peço desculpas pelo inconveniente com o link do Google Sheets. Vamos prosseguir usando o GitHub, que será uma solução mais robusta.
Usando o GitHub para seu Sistema de Orçamentos
Passos para configurar:

    Acesse seu GitHub

    Crie um novo repositório:
        Clique no botão "+" no canto superior direito
        Selecione "New repository"
        Nomeie como "sistema-orcamentos" ou outro nome de sua preferência
        Escolha se deseja que seja público ou privado
        Inicialize com um README
        Clique em "Create repository"

    No seu repositório:
        Clique no botão "Add file" → "Create new file"
        Nomeie como "excel-template-structure.md"
        Copie e cole o conteúdo abaixo:

Estrutura do Sistema de Orçamentos em Excel
Planilhas Necessárias

    Instruções
        Documentação do sistema
        Guia rápido de uso
        Informações de versão

    Configurações
        BDI: 25%
        Encargos Sociais: 112,5%
        Dados da empresa
        Configurações gerais

    Insumos
        Lista completa de insumos
        Colunas: Código, Descrição, Unidade, Preço Unitário, Fonte

    Composições
        Lista de composições de serviços
        Detalhamento de composições com insumos
        Cálculo automático de preços

    Obras
        Orçamento hierárquico
        Estrutura de níveis (1, 1.1, 1.1.1)
        Totalização automática
        Cálculo com BDI

    Relatórios
        Curva ABC
        Resumos por etapa
        Gráficos de distribuição

Fórmulas Principais
Cálculo de BDI
=Preço*(1+BDI%)```
Copiar


### Totalização de Níveis

=SUMIFS(H:H, A:A, ">"&A4, A:A, "<"&(A4+1))```
Copiar


### Cálculo Total Composição

=SUMPRODUCT(Quantidade*PreçoUnitário)```
Copiar


    Adicione uma estrutura de banco de dados:
        Crie outro arquivo chamado "database-schema.sql"
        Copie e cole o modelo do banco de dados que compartilhei anteriormente

    Notifique-me quando estiver pronto
        Compartilhe o link do seu repositório (se for público)
        Ou adicione-me como colaborador (se for privado)

Assim que você criar o repositório, poderei:

    Fornecer mais arquivos e códigos prontos

    Adicionar um modelo Excel completo

Inserir código fonte para a aplicação

Adicionar documentação detalhada
