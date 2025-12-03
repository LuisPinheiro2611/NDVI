# Geração de índices de vegetação com Google Earth Engine e Python

Este projeto utiliza o *Google Earth Engine (GEE)* em conjunto com *Python* no Google Colab para gerar  índices de vegetação de uma área específica, definida por meio de um arquivo shapefile.

## Funcionalidades

- Autenticação e inicialização da API do GEE
- Leitura e reprojeção da área de estudo a partir de shapefile com geopandas
- Conversão da geometria para o formato aceito pelo GEE
- Coleta de imagens do satélite *Sentinel-2* (pode ser adaptado para outros sensores)
- Cálculo do NDVI, NDRE, NDWI, SAVI, EVI e VARI a partir de suas fórmulas e bandas
- Recorte da imagem com base na área de interesse
- Visualização interativa usando geemap 
- Adição de legenda de cores e zoom automático na AOI
- Exportação da imagem NDVI em formato *GeoTIFF*


## Requisitos

- Conta ativada no [Google Earth Engine](https://signup.earthengine.google.com/)
- Ambiente Google Colab ou local com:
  - earthengine-api
  - geopandas
  - geemap


## Acesso rápido ao notebook
n
[*Clique aqui para abrir o notebook no Google Colab*](https://colab.research.google.com/drive/1OTS9AG5KoKOrg1-FCNwUhTpNRsadACC9?usp=sharing)

Instale com:

```bash
pip install earthengine-api geopandas geemap matplotlib



