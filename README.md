# azure-knowledge-mining-workshop

This repo is a simple workshop that builds a Knowledge Mining solution from scratch in Azure leveraging Azure Search, Azure Cognitive Services, Custom Vision, Form Recognizer and custom web services in general.

(Work in Progress)

# Helper Tool: jupyter cs-configuration.ipynb

This jupyter configuration notebook (cs-configuration.ipynb) helps to easily customize an Azure Search Index/Indexer and SkillSet (see .json file for each) to develop a Cognitive Search solution. The notebook enables to delete/re-create each item and kick off the indexer + wait on status to then run test queries and quickly iterate to develop your custom cognitive search solutions.

The template adds a custom '#11' skill leveraging an Azure AI Custom Vision model endpoint. The rest of the skills come from the Azure Knowledge Mining Accelerator.
