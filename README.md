### Processador de Dados VigiLab 2025

#### Descrição

Este projeto consiste em um script Python para processar e analisar dados laboratoriais de arboviroses (Dengue, Zika e Chikungunya) do sistema VigiLab para o ano de 2025. O programa processa os dados, calcula estatísticas importantes e gera relatórios detalhados por município e período.

#### Funcionalidades
- Processamento de dados por períodos de 7 dias
- Análise de resultados para Dengue, Zika e Chikungunya
- Cálculo de positividade por município
- Geração de relatórios em Excel com múltiplas planilhas
- Filtros automáticos para limpeza de dados inconsistentes

#### Pré-requisitos
- Python 3.12.9
- Biblioteca Pandas
- Arquivo de dados no formato Excel (.xlsx)

#### Instalação
Clone este repositório: git clone https://github.com/seu-usuario/vigilab-processor.git
Instale as dependências necessárias: pip install pandas openpyxl

#### Como usar
Coloque seu arquivo de dados com nome 'data.xlsx' na mesma pasta do script
Execute o script: python vigilab_processor.py
O resultado será salvo em um arquivo Excel chamado 'TotalVigiLabUrbanas_2025.xlsx'

#### Estrutura do arquivo de saída
O arquivo Excel gerado contém as seguintes planilhas:
- DENGUE: Resultados totais para Dengue
- CHIKUNGUNYA: Resultados totais para Chikungunya
- ZIKA: Resultados totais para Zika
- DENGUE_PERIODOS: Análise temporal para Dengue
- CHIKUNGUNYA_PERIODOS: Análise temporal para Chikungunya
- ZIKA_PERIODOS: Análise temporal para Zika

#### Métricas calculadas
- Amostras Enviadas
- Resultados Inconclusivos
- Resultados Indeterminados
- Resultados Não Reagentes
- Resultados Reagentes
- Resultados Não Detectáveis
- Resultados Detectáveis
- Total de Positivos
- Positividade (%)
- Contribuição

<img width="932" alt="Captura de Tela 2025-02-28 às 12 11 09" src="https://github.com/user-attachments/assets/3ae61143-2510-475c-b54d-72111aa039c6" />


Desenvolvido por Pedro Araújo

Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

Contato
Para mais informações ou dúvidas, abra uma issue no repositório ou envie um e-mail para pedro.arthur@saude.gov.br
