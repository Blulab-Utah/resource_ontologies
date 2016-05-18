# Lexical Resource Ontologies

<p>The files in the repository are the lexical resource ontologies created by and used in the <a href="http://blulab.chpc.utah.edu">BLU Lab</a>. All versions of the ontology are protected under the <a href="https://creativecommons.org/licenses/by/4.0/legalcode">Creative Commons Attribution 4.0 International Public License</a>.</p>

<p>To suggest any edits to the following ontologies, please submit an Issue here.</p>

<p><strong>TermMapping.owl</strong>: This file contains a list of annotation properties to hold preferredTerms, synonymns, misspellings, codes, alternateCodes, and regex. It is imported into all of the other files.</p> 

<p><strong>ConText.owl</strong>: This file contains a set of classes and object properties to specify the components of the ConText algorithm developed by the BLU Lab. The components consist of classes to describe the modifiers, termination terms, pseudo terms and actions needed for an NLP system to extract modifiers related to a potential anchor/target. This file is imported and used by both the Modifer.owl and Schema.owl files.</p>

<p><strong>Modifier.owl</strong>: This file extends the ConText.owl file to include a hierarchy of modifier terms that are beneficial for biomedical NLP information extraction. Also, included are instances that contain the lexical cues for each modifier class.</p>

<p><strong>Schema.owl</strong>: This file contains an NLP schema that models the types of annotations that can be created from NLP systems. It contains a hierarcy of semantic categories that can be associated with certain linguistic and semantic modifiers. This file is imported into a domain ontology to create domain specific variables for extraction. </p>
