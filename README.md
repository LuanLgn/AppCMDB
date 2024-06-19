# AppCMDB

# Estrutura de Documentação do CMDB

## Dashboard

- ICs que vencem em 30 dias
- ICs na Garantia
- Licença de Inventário Automático
- Gráfico ICs X Chamados
- Status dos ICs

## Lançamentos

### Lista de ICs
### Ps: Ics são altamentes importantes para ter um controle de chamados que são realizados em determinado IC e/ou uma medida administrativa 
- Nome
- Vencimento
- Status ICs
- Tipo Status IC
- Tipo de Ativo
- Número de Série
- Patrimônio
- Alocado (o solicitante só consegue ver os ics que estão alocados a ele)
- Proprietário
  - Cliente
  - Área
  - Solicitante
- Exportar
- Importar XLS
- Imprimir QRCode

#### Criar IC

##### Geral

- Modelo de IC
- Nome
- Número de Série

##### Proprietário

- Cliente
- Área
- Solicitante

##### Alocado em

- Status do ICs
- Tipo de Ativo

##### Detalhes

###### Data

- Data de Garantia
- Data de Aquisição
- Data de Vencimento
- Data de Descontinuação do Fabricante
- Data de Finalização do Suporte pelo Fabricante

###### Identificação

- Link
- Descrição
- Patrimônio
- Número Fiscal
- Custo
- TAG
- Plataforma
- Versão
- Modelo
- MAC Address
- IP Address

###### Localização

- Cidade
- UF
- Polo
- Torre
- Ambiente Restrito
- Andar
- Acesso ao Equipamento
- Localização
- Características do Local

###### Prioridades

- Prioridade do Equipamento
- Prioridade do Ambiente
- Prioridade do SLA
- Termo de Responsabilidade - Sim/Não

###### Estoque

- Qtd Estoque
- Qtd estoque mínima para alerta
- Template (chamado)

##### Vínculos

- Fornecedor
- Contrato
- Centro de Custo

##### Inventários

- Inventario Automático
- Inventario Manual 

##### Atributos

- Adicionar atributos

##### Histórico de Transferência

- (em branco)

##### Notificação

- Notificar Vencimento do IC
- Enviar Alerta em X Dias
- Enviar alerta a cada 24 horas
- Enviar histórico de transferência
- Quem notificar - operadores/solicitantes

##### Regras de Visualização e Utilização

- Observações sobre gestão de visualizações e restrições de ICs

##### Chamados

- Código
- Assunto
- Solicitante
- Quantidade

##### Anexos

- Anexar arquivos

### Quadro de IC

- Kanban com os quadros de ICs de acordo com os status de ICs

### Cofre de Senhas

- Cofre de senhas do próprio operador
- É possível somente importar

#### Criar Cofre de Senhas

- Nome
- Cliente
- Login
- Senha
- Permissão
- Descrição

### Inventário Automático

- É possível somente exportar
- É possível converter um equipamento em IC

#### Criar Inventário Automático

- OID - Chave de identificação da máquina
- Nome
- Label

##### Geral

- Fornecedor do Sistema
  - Tipo de Sistema
  - Modelo de Sistema

##### Informações do SO

- Sistema Uptime
- Usuário Logado
- Número de Série
- Versão do SO
- Tag do sistema

##### Informações da Bios

- Versão da BIOS
- Data de Lançamento
- Fabricante da BIOS

##### Placa Mãe

- Nome Placa Mãe
- ID Placa Mãe
- Fabricante
- Banda
- Clock Real
- Clock Efetivo

##### Processadores

- Nome
- Fabricante
- L2 Cache
- Ext Clock
- Carga

##### Memórias

- Localização
- Part Number
- Tipo de Memória
- Capacidade
- Serial Number

##### Programas

- Adicionar programas

##### Armazenamento

- Disco
- Driver CD/DVD
- Driver Controlador
- Unidades

##### Entrada

- Mouse
- Teclado
- Impressoras
- Outros

##### Redes

- Adaptador de Redes

##### Multimídia

- Som
- Vídeo

##### Segurança

- Firewall
- Antivirus

##### Software Licenciados

- Adicionar Licenças

## Cadastro

### Ativos

- Nome do ativo

### Sub-Ativos

- Correlacionar com ativo
- Nome do sub-ativo

### Área

- Nome 
- Cliente
- Departamento
- Local
- (Pode ser um solicitante, departamento ou local)

### Status ICs

- Nome
- Tipo - Operacional, Alerta, Análise, Manutenção, Danificado

### Modelo IC

#### Cadastro

- Nome
- Tipo (Nome do ativo e sub-ativo)
- Custo
- Número de Série
- Patrimônio
- Adicionar atributos

### Centro de Custo

- Adicionar nome do centro de custo principal, exemplo o departamento, a empresa e etc
- Importante adotar um padrão de escritas para que fique mais fácil a leitura. Exemplo ; "ADM - 0001"

## Configurações

### Relatório de Inventários

#### Configurações do relatórios para o slideshow

- Cadastro
  - Nome
  - Tipo
  - Operadores
  - Grupo
  - Colunas
  - Filtros
  - Ordem
  - Envio programado
  - Detalhes do email

### Relatório de ICs

#### Configurações do relatórios para o slideshow

- Cadastro
  - Nome
  - Tipo
  - Operadores
  - Grupo
  - Exibir no dashboard sim/nao ícone
  - Colunas
  - Filtros
  - Ordem
  - Envio programado
  - Detalhes do email

### Inventário Automático

- Licenças
- Total de Licenças
- Download
  - Máquinas Windows
  - Operator Key
  - Ambient Key
  - Label (Opcional)
  - Chave (Opcional)
  - Proxy - Não/Sim
  - Alertas para operador
