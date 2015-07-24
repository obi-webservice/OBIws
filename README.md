### Bioinformatics Web Services ontology (OBIws)

The Bioinformatics Web Services ontology (OBIws) is an ontology that extends the Ontology for Biomedical Investigations (OBI) to build an Ontology that supports consistent annotation of Bioinformatics Web services. We also consider reuse of terms available from the EMBRACE Data And Methods (EDAM) ontology. 

We follow a systematic methodology for enriching OBI with terms to support Web service Annotation. This process involves the design of ontology analysis diagrams for Web services and their subsequent analysis to discover terms that need to be added to the ontology. The methodology has been summarized in the paper: [Enriching the Ontology for Biomedical Investigations (OBI) to Improve its Suitability for Web Service Annotations](http://cs.uga.edu/~jam/home/theses/guttula_thesis/radiantWeb/version3/ICBO_final.pdf)

Current OBIws ontology is focusing on sequence analysis web services. With developed patterns of modeling web services, OBIws can be extended easily to support annotations of different kind web services. Welcome to send your request for new terms to the [issue tracker](https://github.com/obi-webservice/OBIws/issues).  

<b>Available Versions</b>

- OBIws development version
  - Contains all the terms in the OBI ontology plus the web service terms added to it
  - https://raw.githubusercontent.com/obi-webservice/OBIws/master/ontology/OBIws.owl (unstable)
  - Aavailable on the OntoBee.org: http://www.ontobee.org/browser/index.php?o=OBIws

- OBIws release version
  - A trimmed down version that contains the web service terms along with related OBI higher level terms and with all newly added terms with assigned OBIws ids. This version is more suitable to be used with applications.
  - OBIws v1.1: http://purl.obolibrary.org/obo/obi/v1.1/webService.owl 
  - OBIws v1.0: http://purl.obolibrary.org/obo/obi/v1.0/webService.owl
  - OBIws v0.9: http://purl.obolibrary.org/obo/obi/v0.9/webService.owl

The latest release version of the ontology can be accessed by the link:
http://purl.obolibrary.org/obo/obi/webService.owl

The ontology can be viewed on Bioportal website:
http://bioportal.bioontology.org/ontologies/3119

All the Publications related to the project can be found [here](http://mango.ctegd.uga.edu/jkissingLab/SWS/publications.html).

SAWSDL files annotated using the extended OBI ontology can be found on [our project](http://mango.ctegd.uga.edu/jkissingLab/SWS/services.html).
