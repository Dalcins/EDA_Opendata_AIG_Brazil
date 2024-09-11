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
- [Kaggle](https://www.kaggle.com/datasets/nosbielcs/opendataaigbrazil)

## Dicionário de Dados

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

## **Principais Resultados**

Durante a análise exploratória dos dados de ocorrências na aviação brasileira, foram identificados diversos insights importantes, que podem ser úteis para a melhoria da segurança aérea no Brasil. Abaixo estão os principais resultados obtidos:

1. **Classificação das Ocorrências:**
   - A maioria das ocorrências foi classificada como "Incidente" e "Incidente Grave", com um número menor de "Acidentes". Esse dado sugere que, apesar da frequência de ocorrências, grande parte delas não representa uma ameaça crítica à segurança.

2. **Distribuição Geográfica:**
   - As ocorrências foram concentradas principalmente em grandes cidades e centros urbanos com alta movimentação aérea, como São Paulo, Rio de Janeiro e Brasília.
   - Os estados de São Paulo (SP) e Rio de Janeiro (RJ) registraram o maior número de ocorrências, o que está diretamente relacionado ao alto volume de tráfego aéreo nessas regiões.

3. **Natureza das Ocorrências:**
   - As principais causas de ocorrências incluem falhas operacionais, problemas técnicos de manutenção e condições climáticas adversas.
   - Problemas relacionados a falhas de comunicação entre aeronaves e torres de controle também foram destacados, representando uma área de risco que necessita de atenção.

4. **Aeronaves Envolvidas:**
   - Aeronaves equipadas com motores a pistão e turboélices estão mais frequentemente envolvidas em acidentes e incidentes, sugerindo que aeronaves de menor porte ou mais antigas são mais suscetíveis a falhas.
   - Uma correlação foi observada entre o ano de fabricação das aeronaves e o nível de danos: aeronaves mais antigas tendem a sofrer danos mais severos.

5. **Impacto nas Vidas Humanas:**
   - A maioria das ocorrências não resultou em fatalidades, o que é um indicador positivo de segurança. No entanto, houve um pequeno número de acidentes graves que levaram à perda de vidas, evidenciando a necessidade de melhorias contínuas em procedimentos de segurança.

6. **Fatores Contribuintes:**
   - A análise mostrou que muitos dos incidentes e acidentes têm como fatores contribuintes falhas humanas e erros operacionais. Isso reforça a importância de treinamentos rigorosos para pilotos e equipes técnicas.
   - Fatores técnicos, como falhas mecânicas, também tiveram um papel significativo, principalmente em aeronaves mais antigas.

7. **Fases Críticas do Voo:**
   - As ocorrências foram mais frequentes durante as fases críticas do voo, como decolagem e pouso. Esses momentos são considerados de maior risco, o que sugere a necessidade de uma atenção especial durante esses períodos.

Esses resultados fornecem uma visão ampla sobre os fatores que influenciam as ocorrências na aviação brasileira e indicam áreas onde melhorias podem ser implementadas para aumentar a segurança e reduzir o número de incidentes e acidentes no setor.



**Contato**
- Arthur Dalcin : arthurdalcinss@gmail.com
- Arthur Gomes :
- Davi Ribeiro :
- Thais Fernandes :
- Luciano Weber :
   
