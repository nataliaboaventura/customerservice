# Desenvolvimento de KPI’s do Serviço de Atendimento de uma Empresa Antifraude

Este projeto foi desenvolvido por **Natália Boaventura** no curso de **Análise de Dados** da **Escola DNC**. O objetivo principal é metrificar e entender os gargalos do atendimento da empresa antifraude, utilizando bases de dados extraídas da central de atendimento.

## Objetivo

O estudo foca na análise dos chamados recebidos pelos canais de atendimento da empresa, identificando padrões, tempos de resolução e principais motivos de contato. A partir dessas métricas, é possível gerar insights para otimizar o atendimento e melhorar a eficiência do serviço.

## Bases de Dados Utilizadas

Foram utilizadas duas bases de dados fornecidas pela empresa parceira da Escola DNC:

- **Service** - Dados dos acionamentos via e-mail: [Download](https://docs.google.com/spreadsheets/d/e/2PACX-1vRc4sS3L_giFOxOlpxN-YkAhwx2fcaxYbo3p6DWoHxDLAYzMYOZko5gvVbPt2ejwA/pub?output=xlsx)
- **Canais Digitais** - Dados dos acionamentos via chatbot e WhatsApp: [Download](https://docs.google.com/spreadsheets/d/e/2PACX-1vROZSpSw23dER5fqelnvl0MY62nDC0oEP5P_obZ4bfjsmvOFH5kUd_oaqpzE94jtA/pub?output=xlsx)

## Dicionário de Dados

As bases contêm as seguintes informações:

- **Número do Caso** - Identificação do caso no sistema
- **Status** - Status do caso na data de extração do relatório
- **Tipo de Registro do Caso** - Canal de recebimento (E-mail, WhatsApp, Chat)
- **Grupo** - Grupo ao qual o caso pertence (Central de Relacionamento)
- **Proprietário do Caso** - Atendente responsável
- **ID da Conta** - Identificação do cliente
- **Plataforma** - Indica se o cliente possui acesso a serviços diferenciados
- **Data/Hora de Abertura** - Momento de criação do caso
- **Data/Hora de Fechamento** - Momento da resolução do caso
- **Motivo do Caso** - Razão principal do acionamento
- **Submotivo do Caso** - Detalhamento do motivo
- **Frente** - Segmentação do cliente

## Tecnologias Utilizadas

- **Python**
- **Pandas**
- **Seaborn**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

## Principais Etapas do Projeto

1. **Carregamento e Limpeza dos Dados**
   - Remoção de colunas irrelevantes
   - Padronização de valores nulos
   - Ajuste de tipos de dados

2. **Análise Exploratória**
   - Agrupamento por status e motivo do contato
   - Identificação de casos não finalizados
   - Cálculo de tempos de resolução

3. **Geração de KPI’s**
   - Tempo médio de resolução
   - Distribuição de chamados por canal
   - Volume de casos por atendente

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

## Contribuição
Sinta-se à vontade para contribuir com melhorias no projeto. Para isso, faça um fork do repositório, crie uma nova branch para suas modificações e envie um pull request.

## Contato
Dúvidas ou sugestões? Entre em contato comigo através do meu LinkedIn www.linkedin.com/in/natalia-boaventura

