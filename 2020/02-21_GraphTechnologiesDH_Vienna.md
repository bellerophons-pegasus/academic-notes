# Graph Technologies in the Digital Humanities
Modelling the Scholarly Process

* When & Where? 21. & 22. 02. 2020 - Vienna
* [Website](https://graphentechnologien.hypotheses.org/tagungen/graphentechnologien-2020)
* [Programme (PDF)](https://f.hypotheses.org/wp-content/blogs.dir/4521/files/2020/02/Graph-Technologies-Conference-UWien-2020.pdf)
* ![On Twitter][twitter-icon] [#graph2020](https://twitter.com/hashtag/graph2020)

Topics: graphs, network analysis, digital humanities, annotation, natural language processing (NLP), 

## Session 1 - Modelling the Scholarly Process

### Modeling as a Scholarly Process - The Impact of Modeling Decisions on Data-Driven Research Practices

(Aline Deicke, Mainz ![On Twitter][twitter-icon] [@alinedeicke](https://twitter.com/alinedeicke))

* data model as basis for AI
* used CIDOC CRM for data modeling
  * social processes with CRMsoc

  **=>** embrace diversity of data models, but: **publish them** (mapping and matching)

> * [E. Dröge (2010). Leitfaden für das Verbinden von Ontologien, Information Wissenschaft und Praxis 61 (2), 143-147](https://www.phil-fak.uni-duesseldorf.de/fileadmin/Redaktion/Institute/Informationswissenschaft/forschung/wissensrepraesentation/1268059439iwp_61_201.pdf) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/6f79c623bb8afef5b0a4e4cea1c6ad70e56022af/literature.bib#L14-L24)
> * [U. Brandes - G. Robins - A. McCranie - S. Wasserman (2013). What is network science?, Network Science, 1(1), 1–15. DOI: 10.1017/nws.2013.2](https://doi.org/10.1017/nws.2013.2) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/6f79c623bb8afef5b0a4e4cea1c6ad70e56022af/literature.bib#L35-L45)
> * [J. Flanders -- F. Jannidis (2015). Knowledge Organization and Data Modeling in the Humanities](https://nbn-resolving.org/urn:nbn:de:bvb:20-opus-111270) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/6f79c623bb8afef5b0a4e4cea1c6ad70e56022af/literature.bib#L26-L33)
> * [Y. Hui (2012). What is a Digital Object?, Metaphilosophy, 43, 380-395. DOI:10.1111/j.1467-9973.2012.01761.x](https://doi.org/10.1111/j.1467-9973.2012.01761.x) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/6f79c623bb8afef5b0a4e4cea1c6ad70e56022af/literature.bib#L3-L12)
> * [M. Shanks (2007). Symmetrical archaeology, World Archaeology, 39 (4), 589-596. DOI:10.1080/00438240701679676](https://doi.org/10.1080/00438240701679676) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/6f79c623bb8afef5b0a4e4cea1c6ad70e56022af/literature.bib#L47-L57)
> * Tool [arrowtool by A. Jones](http://www.apcjones.com/arrows/), ![GitHub][github-icon] [apcj/arrows](https://github.com/apcj/arrows) -- *library for drawing small graphs*


### Towards Scholarly Modelling with Graph Technology. Data before Schema

(Thomas Efer, Leipzig)

* schemas are good, but what about interoperability?
* Scientific modelling
  * Mental model
  * Data model (and data types)
  * Conceptual model (-> larger and more abstract)
  * Domain model
  * Process model
* TaDiRAH: -> [modeling](https://github.com/dhtaxonomy/TaDiRAH/blob/master/reference/activities.md#modeling)
* Complex example: modelling of representation of names (e.g. Arabic)
  * -> the modeling process already includes thinking of e.g. search, display etc
* "modeling" = "coming to know" 

### Collaborative Modelling of Historical Information and Information Extraction from Sources

(Francesco Beretta, Rhône-Alpes)

> * [Symogih](http://symogih.org/) - a modular system for managing historical information; event centered data model/ontology
> * [OntoME](http://ontome.dataforhistory.org/) - product of project [Data for History](http://dataforhistory.org/); -> CRMhist
> * [Geovistory Toolbox](https://geovistory.com/home) (only with login)
> * Mentioned a video by Harald Sack on YouTube about AI (not found); [Knowledge Engineering with Semantic Web Technologies](https://www.youtube.com/watch?v=eJ9H1SakPoA&list=PLoOmvuyo5UAcBXlhTti7kzetSsi1PpJGR)

### Möglichkeiten der Versionierung RDF-basierter Daten für den wissenschaftlichen (DH-)Diskurs

(Martina Bürgermeister, Graz)

> * [T. Berners-Lee. Semantic Web Stack (image)](https://en.wikipedia.org/wiki/Semantic_Web_Stack); [Original Slides](https://www.w3.org/2000/Talks/1206-xml2k-tbl/slide10-0.html)
* -> Versioning is part of proof
> * [W3C (2010). Provenance XG Final Report](http://www.w3.org/2005/Incubator/prov/XGR-prov/) [`BibTeX`]()
* independent copy (= data dumps)
* change-based (-> save deltas)
>   * [M. Vander Sande -- P. Colpaert -- R. Verborgh -- S. Coppens -- E. Mannens -- R. Van de Walle (2013). R&Wbase: git for triples, in 6th Workshop on Linked Data on the Web, Proceedings, Rio de Janeiro, Brazil. Handle:1854/LU-3254494](http://hdl.handle.net/1854/LU-3254494) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/8725ee2c1b97d8eda7047b0904242cdf5f75e3d7/literature.bib#L69-L79)
>   * [M. Graube -- S. Hensel -- L Urbas (2014). R43ples: Revisions for Triples - An Approach for Version Control in the Semantic Web, in Proceedings of the 1st Workshop on Linked Data Quality co-located with 10th International Conference on Semantic Systems, LDQ@SEMANTiCS 2014.](http://ceur-ws.org/Vol-1215/paper-03.pdf) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/8725ee2c1b97d8eda7047b0904242cdf5f75e3d7/literature.bib#L81-L91)
>   * [P. Meinhardt -- M. Knuth -- H. Sack (2015). TailR: A Platform for Preserving History on the Web of Data, in Proceedings of the 11th International Conference on Semantic Systems (SEMANTICS ’15). DOI:10.1145/2814864.2814875](https://doi.org/10.1145/2814864.2814875) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/8725ee2c1b97d8eda7047b0904242cdf5f75e3d7/literature.bib#L93-L108)
* timestamp based 
>   * [T. Neumann -- G. Weikum (2010). X-RDF-3X: fast querying, high update rates, and consistency for RDF databases, Proceedings of the VLDB Endowment 3 (1–2), 256–263. DOI:10.14778/1920841.1920877](https://doi.org/10.14778/1920841.1920877) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/8725ee2c1b97d8eda7047b0904242cdf5f75e3d7/literature.bib#L110-L125)
> * [R. Taelman -- M. Vander Sande -- J. Van Herwegen -- E. Mannens -- R. Verborgh (2019). Triple Storage for Random-Access Versioned Querying of RDF Archives, Journal of Web Semantics, 54, 4–28. DOI:10.1016/j.websem.2018.08.001](https://doi.org/10.1016/j.websem.2018.08.001) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/dffa3c36586c05c34b69920d73f7dd3e6ee187ea/literature.bib#L127-L137)


## Session 2 - Graphs and Language

### Testing Greek Grammar with Graphs -- an Exploratory Approach to a Treebank

(Nina Čengić, Neven Jovanović ![GitHub][github-icon] [nevenjovanovic](https://github.com/nevenjovanovic), Petra Matović, Zagreb)

* Treebanks for Ancient Greek
  * [Perseus](https://perseusdl.github.io/treebank_data/) and ![GitHub][github-icon] [PerseusDL](https://github.com/PerseusDL)
  * [PROIEL](https://proiel.github.io/) and and ![GitHub][github-icon] [proiel](https://github.com/proiel)
  * [SEMATIA (Helsinki)](https://sematia.hum.helsinki.fi/) (requires login)
  * [Pedalion pedagogical collection (Leuven)](http://en.pedalion.org/treebanks) and ![GitHub][github-icon] [perseids-publications/pedalion-trees](https://github.com/perseids-publications/pedalion-trees/)
  * [Collection of sentences annotated by Vanessa Gorman (Nebraska)](https://vgorman1.github.io/) and ![GitHub][github-icon] [perseids-publications/gorman-trees](https://github.com/perseids-publications/gorman-trees/)
* Are not mentioned in printed publications
* Tool for annotations: [Arethusa](https://www.perseids.org/tools/arethusa/app/#/) and ![GitHub][github-icon] [alpheios-project/arethusa](https://github.com/alpheios-project/arethusa)
* Tool for exploring treebanks ![GitHub][github-icon] [nevenjovanovic/explore-treebanks-xquery](https://github.com/nevenjovanovic/explore-treebanks-xquery)

### Modelling the Semantic Relations within Texts Using the UD NLP Tools for Syntactic Parsing, Neo4j Graph Database for Storing and igraph for Network Analysis

(Benedikt Perak, Rijeka)

* Worked on parlament protocols from Croatia (CroParl)
* Tool [igraph]() for network analysis
* *Words are vessels, like ships, that are sent from brain to brain*
* ![GitHub][github-icon] [rodik/Sabor](https://github.com/rodik/Sabor)
* Tool [py2neo](https://py2neo.org/v4/), a client library and toolkit for working with Neo4j from within Python
* Tool [UDPipe](https://cran.r-project.org/web/packages/udpipe/vignettes/udpipe-annotation.html), R package for NLP

### Graphenmetriken als Alternative zu statistischen Maßen in sprachwissenschaftlichen Fragestellungen

(Anna Shadrova, HU Berlin)

* [Kobalt-DaF](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/kobalt-daf), a network for German as foreign language
> * [A. Kilgarriff (2005). Language is never ever ever random, Corpus Linguistics and Linguistic Theory 1 (2), 263-276. DOI:10.1515/cllt.2005.1.2.263](https://doi.org/10.1515/cllt.2005.1.2.263) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/8725ee2c1b97d8eda7047b0904242cdf5f75e3d7/literature.bib#L139-L150)
* Louvain modularity
  * graph distance
  > * [P. Wills -- F. G. Meyer (2020). Metrics for graph comparison: A practitioner’s guide, PLoS ONE 15 (2). DOI:10.1371/journal.pone.0228728](https://doi.org/10.1371/journal.pone.0228728) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/8725ee2c1b97d8eda7047b0904242cdf5f75e3d7/literature.bib#L152-L161)
  * assortativity
  * markov chains
* Tools [NetworkX](https://networkx.github.io/), Python for network analysis; [Python and NetworkX](https://python-louvain.readthedocs.io/en/latest/), community detection



<!-- https://github.com/carlsednaoui/gitsocial -->
[twitter-icon]: http://i.imgur.com/wWzX9uB.png (on Twitter)
[github-icon]: http://i.imgur.com/9I6NRUm.png (on GitHub)
<!-- own icons -->
[slides-icon]: https://raw.githubusercontent.com/bellerophons-pegasus/academic-notes/master/icons/slide-icon.png
