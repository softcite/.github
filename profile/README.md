# Softcite README page

Softcite is a project to improve the visibility of research software.  We produce datasets, software, and papers.

## Datasets

### Extracted software mentions from publicatons

- [Softcite software mention extractions from ~26 million open access publications, 2025](https://doi.org/10.5281/zenodo.14991355)
  - [Sample Analysis](https://github.com/softcite/softcite-extractions-parquet-analysis)

- [Softcite software mention extractions from the CORD-19 publications ](https://zenodo.org/records/5235661)

### Manually annotated Gold standard dataset of software mentions

- [Softcite Dataset v2](https://zenodo.org/records/7995565)
  - [Annotation Scheme](https://github.com/softcite/software-mentions/blob/master/doc/annotation_guidelines_tei_xml.md) 
- (archived) [Softcite Dataset v1](https://zenodo.org/records/4445202)

## Tools

### Mention Extraction Tool chain

Go from a folder of PDFs to XML extracted full text annoated with software mentions.

- [Softcite Mention Extractor Example Notebook](https://github.com/softcite/mentions_pipeline_notebook)
- [Softcite Mention Extractor client](https://github.com/softcite/software_mentions_client)
- [Softcite Mention Extractor Server](https://github.com/softcite/software-mentions)

### Browser for Extractions

We have an infrastructure to build a website that provides a browser to a database created from software extractions.

- [Softcite Knowledge Base](https://github.com/softcite/softcite_kb)

## Papers

- Du, C., Cohoon, J., Lopez, P., & Howison, J. (2022). Understanding progress in software citation: a study of software citation in the CORD-19 corpus. PeerJ Computer Science, 8, e1022. https://doi.org/10.7717/peerj-cs.1022

- Lopez, P., Du, C., Cohoon, J., Ram, K., & Howison, J. (2021). Mining Software Entities in Scientific Literature: Document-level NER for an Extremely Imbalance and Large-scale Task. Proceedings of the 30th ACM International Conference on Information & Knowledge Management, 3986–3995. https://doi.org/10.1145/3459637.3481936

- Du, C., Cohoon, J., Lopez, P., & Howison, J. (2021). Softcite dataset: A dataset of software mentions in biomedical and economic research publications. Journal of the Association for Information Science and Technology, 72(7), 870–884. https://doi.org/10.1002/asi.24454

### Associated Papers

- Bassinet, A., Bracco, L., L’Hôte, A., Jeangirard, E., Lopez, P., & Romary, L. (2023). Monitoring the production and the openness of research data and software in France:Large-scale Machine-Learning analysis of scientific PDF. https://github.com/Barometre-de-la-Science-Ouverte/bso3-techdoc/blob/master/methodology/bso3.pdf

- Andrew Nesbitt, Boris Veytsman, Daniel Mietchen, Eva Maxfield Brown, James Howison, João Felipe Pimentel, Laurent Hèbert-Dufresne, and Stephan Druskat. 2024. Biomedical Open Source Software: Crucial Packages and Hidden Heroes. arXiv, https://doi.org/10.48550/arXiv.2404.06672

## Known users of Softcite

Ironically (but not at surprisingly) we don't have an automated way to know who is using Softcite Mention extractor or other data products, but here are some known projects.

### Using extraction models
- DataSeer <https://dataseer.ai/>
- EU Funded SoFAIR project <https://sofair.org/>

### Using gold standard annotations
The Chan Zuckerberg Foundaton used the Softcite software mentions annotations dataset to train the model CZI used in creating the CZI software mentions dataset: <https://arxiv.org/abs/2209.00693>

