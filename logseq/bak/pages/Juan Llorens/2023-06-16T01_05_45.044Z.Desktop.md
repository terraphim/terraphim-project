#website [Juan Llorens (researchgate.net)](https://www.researchgate.net/profile/Juan-Llorens)
#selfdescription Juan Llorens is Professor at the Informatics Department of the Carlos III University of Madrid – Spain (www.uc3m.es), Dr. Llorens is the leader of the KR Group (Knowledge Reuse Group) within the University. His current research involves the study of knowledge technologies and system engineering techniques integration towards Software and Systems Reuse and quality measurement. He is technical director of the INCOSE's Spanish Chapter (International Council on Systems Engineering - www.incose.org)
	**Disciplines**
		Information Science
		Information Systems (Business Informatics)
		Software Engineering
	**Skills and expertise**
		Requirements Engineering
		Software Reuse
		Quality Systems
		SysML
		Unified Modeling Language
		Software Quality Management
		Software Design
		Software Engineering
		Systems Engineering
		Software Architecture
		Verification
		Ontologies
		Knowledge Management
		Thesauri
		Use Cases
		Semantics
		Information Science
		Object-Oriented Programming
	**Languages**
		Spanish
		English
		Swedish
#post [Towards a Methodology for Knowledge Reuse Based on Semantic Repositories | Request PDF (researchgate.net)](https://www.researchgate.net/publication/325609127_Towards_a_Methodology_for_Knowledge_Reuse_Based_on_Semantic_Repositories)
	(Fraga et al., 2019)
	#website  [trc-research/oslc-km (github.com)](https://github.com/trc-research/oslc-km)
	#thesis Although reuse is generally considered a good practice within software engineering, several problems dissuade its industrial application and a new viewpoint is needed.
	#research_question  What constraints reuse in industrial applications?
	#role [[Semantics engineer]] #corresponds  [[Product manager]] [[Terraphim]]
	#concept [[*Reuse]] [[*Systematic reuse]] #corresponds  [[Context]] [[Model of situation]] [[Modularity of definitions]] [[*Compositionality]]
	#concept  [[*Universal Knowledge Reuse Methodology (UKRM)]] #corresponds [[Method]] [[Roam-Export-1647521940416/Viewpoint]] UKRM makes reuse independent of the type of content, the context where it will be reused, and even the user that demands it.
	#concept [[*Semantic content]] #corresponds  [[Terraphim]]
#post [(PDF) Enabling System Artefact Exchange and Selection through a Linked Data Layer (researchgate.net)](https://www.researchgate.net/publication/330293084_Enabling_System_Artefact_Exchange_and_Selection_through_a_Linked_Data_Layer)
	#website [OSLC Core Version 3.0. Part 1: Overview (oasis-open-projects.org)](https://docs.oasis-open-projects.org/oslc-op/core/v3.0/os/oslc-core.html)	
	#thesis Successful reuse will come with sophisticated software components storage, representation and retrieval techniques, and one of that are based on the Linked Data, generated from SKOS artefacts. That comprises the OSLC approach.
	#research_question  How can we improve reuse with the search over knowledge graph generated from the project's artefacts? 
	#role [[*MBSE method engineer]] #corresponds  [[Product manager]]
	----
	#concept  [[*OSLC (Open Services for Lifecycle Collaboration)]]  #corresponds [[Terraphim]] [[Mirroring hypothesis]] [[Conway's law mirroring hypothesis]]
		#concept  [[*Artefact reuse]] #corresponds  [[Interchangeability]] [[Interoperability]] [[Metadata]] [[Metacontext]]
		Software and system artefact reuse [Mili et al., 1995] is commonly defined as a process to systematically specify, produce, classify, retrieve and adapt software-based artefacts for the purpose of using them in a development process.
		#concept [[*Principles of reuse]] abstraction, selection, specialization and integration #corresponds  [[Interchangeability]] [[Interoperability]] [[Metacontext]]
		#concept [[*Reusability factor of system artefacts]]  #corresponds  [[Abstraction]]
		#concept [[*Knowledge representation paradigm]] this problem still persists since a suitable representation format (and syntax) can already be reached in several ways [Davis et al., 1993]
			#concept  [[*Knowledge strategy]] #corresponds  [[Metadata]] [[Work product]] [[Framework]] [[Metacontext]] a knowledge strategy is required to really represent, store and search system artefacts metadata and contents.
			#concept [[*Knowledge graph]] #corresponds [[Terraphim]] [[Work package]]
			#concept [[*Knowledge item]] #corresponds  [[Modularity of definitions]] [[Method]] [[Chains and circles of communication]] V-model in [[MBSE]] as [[ANT translation]]
				#concept  [[*Artefact]] These centralized repositories represent artefacts as a set of metadata that are linked to a system artefact (content). #corresponds  [[System model]]
						Although in some cases, the use of metadata can be useful to look up artefacts by filtering certain properties, it seems too simple to really enable the proper reuse of the knowledge embedded in system artefacts.
					#definintion Ios_km:Artefact. A container of relationships between concepts and metaproperties to semantically describe any piece of information. It is the basis for the creation of an underlying semantic network.
			#concept  [[*Relationship]]	 #corresponds  [[Fact type]]
				#definintion  Ios_km:Relationship. A relationship represents a link between any set of resources. It is possible to add semantics and it can contain any number of elements representing binary, ternary or even n-ary relationships.
			#concept  [[*MetaData]] #corresponds  [[Metadata]]
				#definintion  Ios_km:MetaData. A tag-value attribute representing typical metadata properties. [Dublin Core](https://www.dublincore.org/specifications/dublin-core/) is used here to represent such information. Both can be any type of resource or, more specifically, concepts.
			#concept  [[*Repository for systematic reuse]] #corresponds  [[Formal representation]] [[Metadata]] [[System model]] [[Domain model]] [[Terraphim]] [[Linked data]] [[Interoperability]]
				#corresponds  #requirement A language for representing any artefact’s metadata and contents.
				#corresponds  #requirement  A system for indexing and retrieval.
				#corresponds  #requirement  A standard input/output interface (data shape+REST+RDF) to share and exchange artefact metadata and contents.
				#concept  [[*OSLC KM|*Data shape for Knowledge Management]] #corresponds  [[Terraphim]] [[SKOS]]
				#concept  [[*Data shape for representing system artefacts]]
				#concept  [[*Interoperability CRYSTAL]] “Interoperability Specification – V3” of the CRYSTAL project and [IOS V2 Deliverable (crystal-artemis.eu)](https://www.crystal-artemis.eu/fileadmin/user_upload/Deliverables/CRYSTAL_D_601_023_v3.0.pdf)
				#concept  [[*Query]] #corresponds  [[Terraphim]] [[Text architecture, Narrative]]
			#concept  [[*Shape|*Type of resource]] #corresponds  [[Linked data]]
			#concept  [[*Data exchange]] #corresponds  [[Interoperability]] data exchange does not necessarily imply reuse.

-----
#post [(PDF) Project proposal for SEMSE: Semantic Metadata Search TIN 2007-67153 (researchgate.net)](https://www.researchgate.net/publication/220046062_SEMSE_Semantic_Metadata_Search_TIN_2007-67153)
	#thesis 
	#research_question 
	#role #corresponds 
	#concept #corresponds 
#post [(PDF) A methodology for semantic qualification of schemas (researchgate.net)](https://www.researchgate.net/publication/220046035_A_methodology_for_semantic_qualification_of_schemas)
	#thesis 
	#research_question 
	#role #corresponds 
	#concept #corresponds 
#post [(PDF) Training Initiative for New Software/Enterprise Architects: An Ontological Approach (researchgate.net)](https://www.researchgate.net/publication/220864868_Training_Initiative_for_New_SoftwareEnterprise_Architects_An_Ontological_Approach)
	#thesis 
	#research_question 
	#role #corresponds 
	#concept #corresponds 
#backlog 
	#post [(PDF) Formal ontologies and data shapes within the Software Engineering development lifecycle (researchgate.net)](https://www.researchgate.net/publication/335152945_Formal_ontologies_and_data_shapes_within_the_Software_Engineering_development_lifecycle)
		#thesis In this document, an initial review of the different approaches to model and exchange data of software artifacts is done to finally evaluate and discuss the proper mechanisms to technically support the upcoming needs in the Software Engineering development lifecycle. Keywords: software development lifecycle; ontologies; data shapes; interoperability; knowledge representation
		#research_question The application of the Linked Data principles to exchange data in the software development lifecycle is gaining momentum. Software artifacts reuse via interoperability is a key enabler for boosting collaboration in the development of complex software systems. The concept of continuous engineering is becoming a reality since it is possible to integrate data and services under common protocols and data models.
		#role #corresponds 
		#concept #corresponds 
	#post [(PDF) The Need for an Information‐based Approach for Requirement Development and Management (researchgate.net)](https://www.researchgate.net/publication/336108789_The_Need_for_an_Information-based_Approach_for_Requirement_Development_and_Management)
		#thesis 
		#research_question 
		#role #corresponds 
		#concept #corresponds 
	#post [(PDF) An Analysis of Safety Evidence Management with the Structured Assurance Case Metamodel (researchgate.net)](https://www.researchgate.net/publication/309005707_An_Analysis_of_Safety_Evidence_Management_with_the_Structured_Assurance_Case_Metamodel)
		#thesis 
		#research_question 
		#role #corresponds 
		#concept #corresponds 
	#post [(PDF) Reuse of Physical System Models by means of Semantic Knowledge Representation: A Case Study applied to Modelica (researchgate.net)](https://www.researchgate.net/publication/300466040_Reuse_of_Physical_System_Models_by_means_of_Semantic_Knowledge_Representation_A_Case_Study_applied_to_Modelica)
		#thesis 
		#research_question 
		#role #corresponds 
		#concept #corresponds 
	#post [(PDF) Software Engineering Research: The Need to Strengthen and Broaden the Classical Scientific Method (researchgate.net)](https://www.researchgate.net/publication/220046077_Software_engineering_research_The_need_to_strengthen_and_broaden_the_classical_scientific_method)
	#thesis 
	#research_question 
	#role #corresponds 
	#concept #corresponds 