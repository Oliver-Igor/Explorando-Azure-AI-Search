# Explorando-Azure-AI-Search
Explore an Azure AI Search index (UI)
## Recursos do Azure necessários
- Azure AI Search
- Azure AI services
- Storage account

### Carregar documentos para o armazenamento do Azure

### Indexar os documentos

### Consultar o índice

Todo o passo a passo pode ser encontrado detalhadamente em [Explore an Azure AI Search index (UI)](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html#azure-resources-needed)

* `search=*&$count=true` - A consulta de pesquisa retorna todos os documentos no índice de pesquisa.
* `search=locations:'Chicago'` - A consulta pesquisa todos os documentos no índice e filtra revisões com localização em Chicago.
* `search=sentiment:'negative'` - A consulta pesquisa todos os documentos no índice e filtra revisões com sentimento negativo.

## O propósito final é implementar essas buscas dentro de uma aplicação e, assim, realizar buscas automatizadas de forma prática.
