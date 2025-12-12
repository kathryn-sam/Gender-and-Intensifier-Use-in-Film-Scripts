# Men and Women use Similar Levels of Intensifiers in English Movie Dialogs

This repository includes code and data for the project 'Men and Women use Similar Levels of Intensifiers in English Movie Dialogs.'

The aim of this project was to examine potential gender differences in intensifier use among movie characters while controlling for screenwriter gender, and to examine whether year of movie release
moderated these differences. The project uses files from the Cornell Movie Dialogs Corpus. 

This project was part of the course PSY-PC 7500: Language Analytics

## Repository Organization
### CornellMovieDialogsCorpus
Original files from the Cornell Movie Dialogs Corpus. They were retrieved from [Cristian Danescu-Niculescu-Mizil's webpage](https://www.cs.cornell.edu/~cristian/Chameleons_in_imagined_conversations.html)
(link not functional as of Dec 12, 2025). The data is also available on [Convokit](https://convokit.cornell.edu/).

### ProcessedData
This includes data files generated and used during analysis. A detailed description is in the respective folder. 

### IntensifierLists
This includes the list of single word intensifiers as well as the dictionary of multi-word expressions and their part-of-speech tags that were used in the analysis.

### AnalysisScripts
Scripts used for data wrangling, NLP processing, and statistical analyses. Their output can be found in the ProcessedData folder.
The MWE Pipeline Refinement subfolder involves refining the part-of-speech tags for multiword expressions and comparing it to a pipeline using dependency parsing.

