# EDA_Opendata_AIG_Brazil

## Desenvolvedores

- Arthur Dalcin 
- Arthur Gomes 
- Davi Ribeiro 
- Thais 
- Luciano 


## Visão Geral

Este projeto realiza uma **Análise Exploratória de Dados (EDA)** sobre as **ocorrências de aviação no Brasil**, utilizando dados disponibilizados publicamente pela **Agência Nacional de Aviação Civil (ANAC)** e/ou **Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA)**. O objetivo é entender os padrões, tendências e principais fatores relacionados a esses incidentes.

## Objetivos

- Realizar uma análise descritiva dos dados de ocorrências na aviação
- Identificar padrões e tendências relevantes no setor aéreo brasileiro
- Visualizar insights importantes por meio de gráficos e relatórios estatísticos


## Estrutura do Projeto

O projeto é dividido nas seguintes seções:

1. **Coleta de Dados**: Dados obtidos de fontes públicas confiáveis.
2. **Limpeza de Dados**: Tratamento de dados faltantes, duplicados ou inconsistentes.
3. **Análise Exploratória de Dados (EDA)**:
   - Análise descritiva (frequência de ocorrências, localização, categorias).
   - Identificação de causas e tipos de acidentes.
5. **Visualização**: Geração de gráficos para apresentação dos dados analisados.
6. **Conclusões**: Interpretação dos resultados e insights obtidos.

## Fontes de Dados

Os dados utilizados neste projeto foram extraídos das seguintes fontes públicas:
- [Portal de Dados Abertos do CENIPA](https://dados.gov.br/dataset/ocorrencias-aeronauticas)
- [Kaggle]([https://www.anac.gov.br/assuntos/dados-e-estatisticas](https://www.kaggle.com/datasets/nosbielcs/opendataaigbrazil))

### Dicionário de Dados

## Entendimento dos Dados

Abaixo está uma descrição detalhada das colunas presentes no dataset de ocorrências na aviação brasileira.

| **Coluna**                         | **Descrição**                                                                 |
|------------------------------------|-------------------------------------------------------------------------------|
| `codigo_ocorrencia`                | Código único que identifica a ocorrência de aviação.                          |
| `ocorrencia_classificacao`         | Classificação da ocorrência (e.g., acidente, incidente grave).                |
| `ocorrencia_tipo`                  | Tipo específico da ocorrência (e.g., colisão, falha mecânica).                |
| `ocorrencia_dia`                   | Data em que a ocorrência aconteceu.                                           |
| `ocorrencia_horario`               | Horário exato em que a ocorrência foi registrada.                             |
| `ocorrencia_cidade`                | Cidade onde a ocorrência foi registrada.                                      |
| `ocorrencia_uf`                    | Unidade federativa (estado) onde ocorreu o evento.                            |
| `ocorrencia_pais`                  | País onde a ocorrência foi registrada.                                        |
| `ocorrencia_aerodromo`             | Nome do aeródromo próximo ou envolvido na ocorrência.                         |
| `aeronave_matricula`               | Matrícula da aeronave envolvida na ocorrência.                                |
| `aeronave_equipamento`             | Equipamento utilizado pela aeronave (e.g., tipo de aeronave, se é helicóptero, jato). |
| `aeronave_fabricante`              | Fabricante da aeronave envolvida (e.g., Boeing, Airbus).                      |
| `aeronave_modelo`                  | Modelo específico da aeronave (e.g., Boeing 737).                             |
| `aeronave_tipo_motor`              | Tipo de motor da aeronave (e.g., turbofan, turboélice).                       |
| `aeronave_quantidade_motores`      | Número de motores da aeronave.                                                |
| `aeronave_peso_maximo_decolagem`   | Peso máximo de decolagem da aeronave.                                         |
| `aeronave_quantidade_assentos`     | Quantidade de assentos disponíveis na aeronave.                               |
| `aeronave_ano_fabricacao`          | Ano de fabricação da aeronave.                                                |
| `aeronave_pais_registro`           | País de registro da aeronave.                                                 |
| `aeronave_categoria_registro`      | Categoria de registro da aeronave (e.g., comercial, privado).                 |
| `aeronave_segmento_aviacao`        | Segmento da aviação a que a aeronave pertence (e.g., aviação geral, comercial).|
| `aeronave_origem_voo`              | Local de origem do voo da aeronave.                                           |
| `aeronave_destino_voo`             | Destino do voo da aeronave.                                                   |
| `aeronave_fase_voo`                | Fase do voo em que a ocorrência aconteceu (e.g., decolagem, cruzeiro).        |
| `aeronave_tipo_operacao`           | Tipo de operação realizada pela aeronave (e.g., transporte de passageiros, carga).|
| `aeronave_nivel_dano`              | Nível de dano à aeronave resultante da ocorrência (e.g., leve, grave).        |
| `quantidade_fatalidades`           | Número de fatalidades associadas à ocorrência.                                |
| `quantidade_fatores_contribuintes` | Número de fatores que contribuíram para a ocorrência.                         |
| `dia_extracao`                     | Data em que os dados foram extraídos.                                         |


## Ferramentas Utilizadas

- **Linguagem**: Python 3.11.9
- **Bibliotecas**:
  - `pandas`: Manipulação e análise de dados.
  - `matplotlib` e `seaborn`: Visualização de dados.
  - `numpy`: Operações matemáticas e estatísticas.
  - `plotly`: Criação de gráficos interativos.
  - `jupyter notebook`: Ambiente para análise e visualização.

## Instalação e Execução

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/seu-usuario/EDA_Opendata_AIG_Brazil.git
   cd EDA_Opendata_AIG_Brazil
   
2. **Instale as Dependências**:
   ```bash
   pip install -r requirements.txt

3. **Execute a Análise: Abra o arquivo Jupyter Notebook e execute as células para rodar a análise exploratória:**:
   ```bash
   jupyter notebook EDA_Opendata_AIG_Brazil.ipynb

## Principais Resultados ALTERAR ESSA PARTE
- Distribuição de Ocorrências por Ano: Identificação de anos com maior concentração de incidentes.
- Tipos de Ocorrências: Análise dos diferentes tipos de eventos (incidentes, acidentes).
- Fatores Contribuintes Mais Comuns: Fatores recorrentes nas ocorrências.
- Regiões Mais Impactadas: Localidades com maior número de ocorrências registradas.
**Conclusão** ALTERAR
Este projeto fornece uma análise detalhada dos dados de ocorrências na aviação brasileira, auxiliando na identificação de padrões relevantes. As visualizações e insights gerados podem ser utilizados para melhorar as políticas de segurança e a prevenção de acidentes no setor.


**Licença**
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo LICENSE para mais detalhes.

**Contato**
- Arthur Dalcin :
- Arthur Gomes :
- Davi Ribeiro :
- Thais :
- Luciano :
   
