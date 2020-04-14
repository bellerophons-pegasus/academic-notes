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

## Session 3 - Short Presentations (15 min)

### A Comparison of Graph and Collection-based Representations of Early Modern Biographical Archives

(Meadhbh Healy, Thomas O'Connor, John Keating, Maynooth Univ.)

* About data integrity in graph databases
* Comparison of Neo4j an dMongoDB
  * time to get data in and time to get data out (no indexing in Neo4j used)
  * comparison of features
* Did not write down conclusion
  
### Famine and Feast: The Problem of Sources for Linked Data Creation

(Rainer Simon , AIT Austria ![On Twitter][twitter-icon] [@aboutgeo](https://twitter.com/aboutgeo) and Rebecca Kahn, HU Berlin ![On Twitter][twitter-icon] [@rebamex](https://twitter.com/rebamex))

* About [Pelagios project](http://pelagios.org/) (![GitHub][github-icon] [pelagios](https://github.com/pelagios); ![On Twitter][twitter-icon] [@PelagiosNetwork](https://twitter.com/pelagiosnetwork); pelagios-network@googlegroups.com) and [Recogito](https://recogito.pelagios.org/) for annotation
* [The Homer Multitext Project](http://www.homermultitext.org/)
* ![GitHub][github-icon] [alan-turing-institute/lwm_GIR19_resolving_places](https://github.com/alan-turing-institute/lwm_GIR19_resolving_places), *Resolving Places, Past and Present: Toponym Resolution in Historical British Newspapers Using Multiple Resources*

### Working Collaboratively on Graphs

(Marco Petris, Hamburg)

* [Computer Assisted Text Markup and Analysis (CATMA)](https://catma.de/), for annotating texts
* [forTEXT](https://fortext.net/), helps in analysing digital texts
* Did actual collaboration via git


### SPARQLing Ogham Stones - Neue Analysemöglichkeiten analoger Editionen durch Digitalisierung in Wikidata

(Sophie C. Schmidth, Köln ![On Twitter][twitter-icon] [@idhrenil](https://twitter.com/idhrenil) and Florian Thiery, Mainz ![On Twitter][twitter-icon] [@fthierygeo](https://twitter.com/fthierygeo))

* Using Wikidata for Ogham stones; [ogham.link](http://ogham.link/); ![GitHub][github-icon] [ogi-ogham](https://github.com/ogi-ogham)


### The Socinian Correspondence: A Graph-based Digital Scholarly Edition -- Generic Tools and Approach

(Patrick Toschka, Julian Jarosch, Andreas Kuczera, Mainz)

![Slides][slides-icon] [Slides](https://digicademy.github.io/2020-02-21_socinian_correspondence/)

* Digital edition of about 2133 letters
* Tool [eXGraphs](https://lod.academy/site/tools/digicademy/exgraphs) for extracting from XML into graph
* -> [LOD.ACADEMY](https://lod.academy/site/)
* Tool [GRACE](https://lod.academy/site/tools/digicademy/grace) a proof of concept for graph content editing

### Using Graph Technologies to Interconnect and Enrich Public-Domain Music Resources

(David M. Weigl and Werner Goebl, Vienna)

![Slides][slides-icon] [Slides](https://docs.google.com/presentation/d/1RyaoLOrr-IU7mPHO_6Ahn8bd056tGO3ZDqkPOClepfw/)

* About project [TROMPA](https://trompamusic.eu/) ![On Twitter][twitter-icon] [@trompamusic](https://twitter.com/trompamusic)
  * aims to interlink and enrich existing repositories
* uses [MEI (Music Encoding Initiative)](https://music-encoding.org/) and [MELD (Music Encoding and Linked Data)](https://github.com/oerc-music/meld)
  * MELD was developed for the [Lohengrin Time Machine, Oxford](https://lohengrin.linkedmusic.org/) and [here](https://um.web.ox.ac.uk/lohengrin)
* used [solidproject.org](https://solidproject.org/) for finding access rights (?)

## Keynote: Tracing our steps: new tools and new standards for academic transparency

(Charlotte Roueché, King's College London (very charismatic keynote))

* Licensing & Copyright first traces and steps to be found in activities of the [Worshipful Company of Stationers](https://en.wikipedia.org/wiki/Worshipful_Company_of_Stationers_and_Newspaper_Makers)
* Elsevier had a loose predecessor: [Elzivir](https://en.wikipedia.org/wiki/House_of_Elzevir); its logo is based on a tree printed in 1653
* Digital Humanities: too much stuff **=>** we are responsible for it; thus have to preserve, disseminate, and share it; ideally: public
* Why link data? Because we can? **=>** for a fuller account
* [P. Lem (2020). Humanities data sharing ‘should consider non-traditional channels’](https://www.researchprofessionalnews.com/rr-news-europe-universities-2020-2-humanities-data-sharing-should-consider-non-traditional-channels/) [`BibTeX`](xxx)
* [SAWS ontology](https://ancientwisdoms.ac.uk/method/ontology/) for describing relations of texts
* [GODOT](https://godot.date/), a gazetteer of calendar dates in different calendar systems
* Recommendations by [ALLEA](https://allea.org/)
  * [N. Harrower -- M. Maryl -- T. Biro -- B. Immenhauser (2020). Sustainable and FAIR Data Sharing in the Humanities. DOI:10.7486/DRI.tq582c863](https://doi.org/10.7486/DRI.tq582c863) [`BibTeX`](xxx)
* *show the process* there is no excuse for not showing it; and there is enough space
* "Linked Ancient Data" cloud
* [FRBRoo](http://www.cidoc-crm.org/frbroo/home-0), a formal ontology intended to capture and represent the underlying semantics of bibliographic information as extension for CIDOC CRM

## Session 4 - Graphs and the Arts

### Redoing Hairballs: Visualizing Complex Arts & Humanities Data in Multiple Spaces and Time

(Florian Windhager ![On Twitter][twitter-icon] [@windhagr](https://twitter.com/windhagr), Saminu Salisu, Eva Mayr, Donau-Uni Krems)

* About visualisation of large graphs
* [T. von Landesberger -- A. Kuijper -- T. Schreck -- J. Kohlhammer -- J. van Wijk -- J.-D. Fekete -- D. Fellner (2011). Visual Analysis of Large Graphs: State‐of‐the‐Art and Future Research Challenges, Computer Graphics Forum, 30, 1719-1749. DOI:10.1111/j.1467-8659.2011.01898.x](https://doi.org/10.1111/j.1467-8659.2011.01898.x) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/3ea4f88d15a7e4815b445574077ab32a5c49607f/literature.bib#L181-L192)
* [F. Beck -- M. Burch -- S. Diehl -- D. Weiskopf (2014). The State of the Art in Visualizing Dynamic Graphs, in: EuroVis - STARs. DOI:10.2312/eurovisstar.20141174](http://dx.doi.org/10.2312/eurovisstar.20141174) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/3ea4f88d15a7e4815b445574077ab32a5c49607f/literature.bib#L194-L204)
* Options vor visualisation
  * linked timeline
  * animation
  * color coding
  * juxtaposition
  * space time cube
  * **->** one method is not enough
* [M. Dörk -- C. Pietsch -- G. Credico (2017). One view is not enough. High-level visualizations of a large cultural collection, Information Design Journal, 23 (1), 39-47. DOI:10.1075/idj.23.1.06dor](https://doi.org/10.1075/idj.23.1.06dor)  [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/3ea4f88d15a7e4815b445574077ab32a5c49607f/literature.bib#L206-L217)
* [Visualization of Cultural Heritage Collection Data: State of the Art](http://collectionvis.org/)
* [polycube project](https://www.donau-uni.ac.at/en/university/faculties/business-globalization/departments/knowledge-communication-management/research/projects/polycube.html)
* ![GitHub][github-icon] [alan-turing-institute/danubevislab](https://github.com/danubevislab), esp. [page with visualisation](https://danubevislab.github.io/)

### Graphbasierte Wege durch Bilderzählungen. Eine digitale Edition von Giovanni Domenico Tiepolos Bildzyklus Divertimento per li Regazzi auf der Grundlage von CIDOC CRM

(Rostislav Tumanov, Gabriel Viehhauser, Alina Feldmann, Barbara Koller, Uni Stuttgart)

* Representing text as graph; [CollateX](https://collatex.net/)
* used [GraphDB](http://graphdb.ontotext.com/) a semantic graph database
* [Erlangen CRM / OWL](http://erlangen-crm.org/), an OWL-DL 1.0 implementation of the CIDOC Conceptual Reference Model (CIDOC CRM).

### Reimnetzwerke als Untersuchungsgegenstand der Mediävistik

(Thomas Jäger, pagina GmbH)

* about the work of Konrad Zwierzina about Reimnetzwerke (network of rhymes)

## Session 5 - Annotation and Networks

### Modelling the Unthought

(Iian Neill ![On Twitter][twitter-icon] [@codexeditor](https://twitter.com/codexeditor), Chiara Palladino, Andreas Kuczera, Mainz)

* About the project [Codex: an atlas of relations](https://community.neo4j.com/t/codex-an-atlas-of-relations/8277)
> * [I. Neill -- A. Kuczera (2019). The Codex – an Atlas of Relations. In: A. Kuczera -- T. Wübbena -- T. Kollatz (eds.) Die Modellierung des Zweifels – Schlüsselideen und -konzepte zur graphbasierten Modellierung von Unsicherheiten (= Zeitschrift für digitale Geisteswissenschaften / Sonderbände, 4). DOI: 10.17175/sb004_008](http://dx.doi.org/10.17175/sb004_008) [`BibTeX`](https://github.com/bellerophons-pegasus/academic-notes/blob/686d97460bc3fdad749597deb8384ce0853e88c8/literature.bib#L219-L228)

* Text-as-a-Graph system
* "stratified annotations", i.e. annotations that overlap; or multilevel annotations
  * standoff properties (modeled in JSON)
* TEI without XML
* represent annotations as a graph
* spatial relations can also be annotated and represented

### Graphtechnologien für die Analyse historischer Netzwerke mit heterogenen Datenbeständen

(Elena Leitner, Julian Moreno-Schneider, Georg Rehm, Sina Menzel ![On Twitter][twitter-icon] [@menzelsina](https://twitter.com/menzelsina), Vivien Petras, Mark Jan-Bludau ![On Twitter][twitter-icon] [@markiaaan](https://twitter.com/markiaaan), Marian Dörk, DFKI GmbH, HU Berlin, FH Potsdam)

* About the project SoNAR (Interfaces to Data for Historical Social Network Analysis and Research, ![On Twitter][twitter-icon] [#sonaridh](https://twitter.com/hashtag/sonaridh), [sonar.fh-potsdam.de](https://sonar.fh-potsdam.de/))
  * combine multiple sources: [GND](https://www.dnb.de/EN/Professionell/Standardisierung/GND/gnd_node.html) (MARC 21, EAD), bibliographic information (MARC 21, EAD), full texts (ATOM, XML)
  * -> all into Neo4j
* Discussion:
  * Is ist possible to get the research question out of the graph?
  * What do people actually use? What not? (User experience)
  
### Early Modern Korea's Localized Yangban Assemblages in Neo4j

(Javier Cha, Robin Wooyeong Na, Seoul National University and Donghyeok Choi, KAIST)

* Looked into changes of social status of families that had [Yangban](https://en.wikipedia.org/wiki/Yangban)
* Digital Korean Studies; prosopographical/ genealogical work
* South Korea has about 100 data bases that ore now [publicly accessible](https://www.data.go.kr/); thriving factor was the production of movies; "databases have a history"
* used [Cytoscape](https://cytoscape.org/)

### Using Graph Models for Annotating Vague and Uncertain Information

(Cristina Vertan, Uni Hamburg)

* vague and uncertain information, i.e. time, geography etc.
  * originating from different translations of two lost manuscripts
* project [HerCoRe](https://www.inf.uni-hamburg.de/inst/dmp/hercore/projects.html)
* used weight of edges and OWL-2 with fuzzy extension
* used [OrientDB](https://orientdb.com/)
* reasoning done with [DeLorean](http://webdiis.unizar.es/~fbobillo/delorean)

## General Discussion

* Logical reasoning for graph data bases?
* Where do we publish?
  * things that where tried out (also the failed ones)
  * process
  * -> try to use what is already there and blend in
    * e.g. [Research Software Engineers (RSE)](https://rse.ac.uk/)
    * [Digital Humanities Quarterly (DHQ)](http://www.digitalhumanities.org/dhq/)
* [The Programming Historian](https://programminghistorian.org/)
* a manual on GitHub was mentioned, but could not find link
* no code peer review
* How to review a website? How to review a digital edition?
  * Keep in sight the scholar work and not the technicalities
  * Charlotte Roueché: Publish reviews in a journal and not somewhere else. Otherwise we are reinventing the wheel, which should be avoided
  * share code! -> sustainable infrastructure

Next conferences
* 2021: Mainz
* 2022: Amsterdam


<!-- https://github.com/carlsednaoui/gitsocial -->
[twitter-icon]: http://i.imgur.com/wWzX9uB.png (on Twitter)
[github-icon]: http://i.imgur.com/9I6NRUm.png (on GitHub)
<!-- own icons -->
[slides-icon]: https://raw.githubusercontent.com/bellerophons-pegasus/academic-notes/master/icons/slide-icon.png
