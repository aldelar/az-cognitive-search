# az-cognitive-search

This repo contains a jupyter configuration notebook (cs-configuration.ipynb) to easily customize an Azure Search Index/Indexer and SkillSet (see .json file for each) to develop a Cognitive Search solution. The notebook enables to delete/re-create each item and kick off the indexer + wait on status to then run test queries and quickly iterate to develop your custom cognitive search solutions.

The template adds a custom '#11' skill leveraging an Azure AI Custom Vision model endpoint. The rest of the skills come from the Azure Knowledge Mining Accelerator.