# Publicação de dados "ICOS" via PORBIOTA

## Introdução
A publicação de dados de GEE através do PORBIOTA deverá ser feita com o uso das melhores referêncas e boas práticas relativamente à publicação de dados `open data` e `FAIR`.

Importa, por isso, identificar quais os padrões de dados e ferramentas utilizados pela respectiva comunidade internacional, sendo que o PORBIOTA se desenvolve num contexto europeu.

Em todo o caso, as soluções adoptadas devem assegurar os `princípios FAIR` são respeitados, de modo garantir que decisões futuras não são comprometidas pelas actuais.

## Padrões de dados

O ICOS adoptou para padrão de dados para os metadados o padrão `INSPIRE` (ver https://www.icos-cp.eu/about-icos-data#Sect4).

O `INSPIRE` (https://inspire.ec.europa.eu/) usa como base a norma `ISO 19115` (da qual é um perfil). A norma `ISO 19115`, por outro lado, pode ser mapeada a outros padrões dados, incluindo o `Ecological Metadata Language (EML)`(https://knb.ecoinformatics.org/#tools/eml). O catálogo https://rdamsc.dcc.ac.uk/msc/m22 mostra o mapeamento entre `ISO 19115` (do qual `INSPIRE` é um perfil) e `EML`.

Recomenda-se, por isso, o uso do padrão `INSPIRE` para dados GEE no PORBIOTA.

## Infraestrutura de publicação de dados

O PORBIOTA ainda não implementou uma plataforma de publicação de dados de GEE. Esta é uma possibilidade a explorar, que pode concretizar-se via uma das seguintes soluções:
- acordo com o ICOS para uso do Carbol Portal (depende da análise dos termos de publicação)
- implementação ao nível nacional da plataforma Carbon Portal, cujo código Open Source está disponível em https://github.com/ICOS-Carbon-Portal. Esta solução depende da alocação de um informático para a implementação.

Como passo intermédio à publicação de dados via PORBIOTA, pode ser usado um repositório genérico de dados. Recomenda-se o uso do **Zenodo** (https://zenodo.org/), porque:
- é uma plataforma suportada de forma persistente, e garante a preservação dos dados
- atribui DOIs aos datasets, facilitando a citação

## Publicação de conjuntos de dados através do zenodo