## Pedro Paulo Fernandes

Trabalho na fronteira entre **saúde coletiva** e **engenharia de dados**: pegar
informação que já é pública por lei e torná-la utilizável na prática.

Diretor de Tecnologia da Informação na **Prefeitura Municipal de Penápolis (SP)**.
Mestrando em **Saúde Coletiva** no IAMSPE e pós-graduando em **Inteligência
Artificial e Ciência de Dados em Saúde** no Hospital Sírio-Libanês.

### Saúde em Dado

[**saudeemdado.com**](https://saudeemdado.com) — os microdados do SUS
transformados em indicadores consultáveis.

Os dados do DataSUS são abertos, mas chegam em formato proprietário, quebrados
por estado e competência, somando dezenas de gigabytes. Antes de qualquer
análise, vão-se semanas em engenharia de dados. O projeto elimina essa etapa:
mortalidade, dengue, internações e nascimentos agregados por município, com taxa
padronizada por idade, intervalo de confiança e excesso de mortalidade.

- **API REST pública**, sem cadastro — `curl` e pronto
- **Downloads em Parquet** com SHA-256 publicado
- **Servidor MCP** ([`saudeemdado-mcp`](https://pypi.org/project/saudeemdado-mcp/))
  para consultar a base em linguagem natural
- **DOI no Zenodo** e `CITATION.cff` para uso acadêmico
- Infraestrutura a **custo zero**, pipeline reproduzível de ponta a ponta

Três compromissos que valem mais que qualquer indicador: só agregados são
publicados (nenhum microdado individual sai da máquina de processamento), toda
limitação é declarada junto do número, e a qualidade do registro é medida e
exposta — há municípios onde a causa de morte não é confiável, e o site diz
quais.

### Onde me achar

[![Site](https://img.shields.io/badge/saudeemdado.com-107752?style=flat)](https://saudeemdado.com)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--6248--2486-a6ce39?style=flat)](https://orcid.org/0009-0008-6248-2486)
[![Lattes](https://img.shields.io/badge/Currículo-Lattes-1f6feb?style=flat)](http://lattes.cnpq.br/6641343625206093)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-pedro--f-0a66c2?style=flat)](https://www.linkedin.com/in/pedro-f-540154408/)
