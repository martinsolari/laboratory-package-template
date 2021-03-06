# Content and Structure of Laboratory Packages for Software Engineering Experiments
Authors: Martin Solari, Sira Vegas, Natalia Juristo

https://doi.org/10.1016/j.infsof.2017.12.016

## Structure of the LP proposal

Our LP proposal is divided into modules. We believe that researchers all have very diverse information needs. Each researcher has a different background and distinct experience in experimentation. We have found that an experiment is usually run by several researchers who play different roles. We believe that the structure of a LP should enable each researcher to easily identify the key information for the task that he or she is performing without having to leaf through pages of information that has nothing to do with the responsibilities of his or her role. The aim of dividing the LP into modules is to cover all the phases of the experimental process and meet the information needs of different researchers depending on what activity of the experimentation process they are to perform in a manner that is clear to all LP users.

The modules constitute separate parts of the document. However, they are explicitly linked to each other so that anyone who wants to read all the documentation instead of focusing on a particular activity will find it easy to navigate from one to another. In our proposal, a module is a structure that is used separately for some experimental activity. For example, the replicating experimenters use one module to train subjects, another to adapt the design and another to record the results of the replication. We have tried to make each module as self-contained as possible in order to satisfy information needs without the researcher having to resort to other parts of the documentation. If necessary, the modules are further divided in order to include more specific information on diverse subtasks. For example, the experiment module is subdivided into sections on experimental design, session operation and data analysis.

We believe that running a replication should also imply upgrading the LP to integrate the new piece of generated evidence that will help to mature the knowledge pursued by the family of experiments (and supported by the LP). After a replication, it should at least be added to the experiment log generating a new module containing the detailed description of the replication and its results. As a result of the replication, however, observations are often made and lessons learned about the experiment itself, the support materials or even the theory. Therefore, a replication may generate a new version of the LP modules containing this information. Note that the generation of new versions of modules should never result in the replacement of earlier versions, that is, the package also acts as a historical record.

Figure 1 shows the main structure of the LP with the name of each module. The directed lines denote the dependencies between modules. This entire structure is the starting point. Elements can then be added to the LP to mitigate the experimental incidents that we have identified. We have tried to design a preliminary structure that is as detailed as possible to cover the information needs and experimentation process activities. Each module is subdivided into sections. These sections provide help for mitigating the missing information detected in the incidents of a particular experimental subtask.

![Figure 1](./lpstructure.png "Figure 1")

The Introduction to the LP module contains information about the LP itself. This module is at a different level of abstraction to the other modules. Whereas the other modules refer to the experiment, this module refers to the actual LP. The Introduction module is designed to provide the LP user with information about the structure and use of the LP. The LP users may be researchers intending to replicate an experiment or researchers setting out to package an experiment for replication by others. The Introduction module denotes the aims of the instrument (LP), possible uses and how it can be enriched. It also includes the suggested communication instances and the particulars of the researchers who should be contacted in order to run a replication.

There are two other types of LP modules: core modules and study modules. The core modules are modules that contain basic information about the experiment and its underlying theory. While there is only one instance of these modules in the LP, there should be more than one version for the purposes of LP configuration management. The core modules must be modified when significant changes are made to the experiments, thus generating new versions. The study modules each match a replication or aggregation conducted as part of the family of experiments. The number of instances of the study modules in the LP is equal to the number of studies that have been conducted. The study modules are added to the structure of the LP with each replication or aggregation, without altering the previous study modules.

The core modules have a higher level of abstraction and contain the groundwork of an experiment. These modules include the theory, the instructions for replicating the experiment and training material. The module with the highest level of abstraction is the experiment theory. It establishes the theoretical framework for conducting the experiment and interpreting the results. All the other modules are directly or indirectly related to the theory module. The experiment module defines the experiment to be replicated. This module includes the instructions for the replicating experimenter, the operational material and the experimental tools. The training module contains all the materials used to train the experimental subjects (if applicable).

The study modules are added to the LP as the replications or aggregations of the experiment are conducted. Instances of these modules can be added for every replication or secondary study carried out with LP data. The replication modules capture information about each replication. The replicating experimenter is expected to add a module of this type describing his or her replication to the LP. Each module includes the description of the adapted design, the resulting data and notes on the replication experience. The aggregation modules are for recording the secondary analyses conducted on the replication data. These modules record anything from the inspection protocols, meta-analyses or other comparison techniques used and the findings of the secondary study.

The evolution module is a special case within the LP. There is only one instance of this module, and it is therefore an experiment module. However, a new section is aggregated to the evolution for each and every one of the replications and aggregations added to the LP. This module serves the purpose of establishing a relationship between the experiment versions and their replications, as well as of picturing how the LP evolves as a whole. For example, when several replications are conducted by different research groups, the experiment often tends to evolve and the experimental objective to change (in order to further generalize the results). This module should reflect the historical evolution of the experiment and the replications to which each version of the experiment is linked.

When it is necessary to modify any part of the experiment, the changes should be made within one and the same module whenever possible. However, there are often external dependencies. In order to make the LP easier to read, module dependencies are one-way only. The lower-level modules depend on the higher-level modules. For example, the replication modules depend on the experiment module, and this depends on the theory module. Generally, this avoids circular references and eases LP evolution.

## Tool: Laboratory Package template

Each module of the proposed LP structure is further divided in section and subsections. This sections are described in detail in a LP template document. The LP template is a tool for the researcher who is responsible of instantiating an experiment. The LP template assigns a correlative number and provides a content description for each section and subsection.

For using the LP template, we suggest to start with simple instantiations of the core modules. The Experiment module aims to capture the most basic information needed to replicate an experiment. The other core modules: Theory, Training, History, could be used when needed to capture additional knowledge or when the content of the Experiment module is larger. These modules could be constructed after the initial effort to capture the baseline experiment. The Training module is aimed to aggregate all the materials used in training. We have found that in academic settings the experiments are usually conducted within a course and it's common that educational materials (both for the student and the teacher) add an important value for the replicating researcher to provide context.

[Laboratory Package template document (Microsoft Word format)](./LaboratoryPackage_template.docx) 

## Tool: Packaging checklist

The proposed LP structure is the groundwork for deploying other improvements to content and writing style. The incidents identified in the diagnosis stage show that many of the problems in the use of the LPs are due to information that is missing or not detailed enough for replication. On one hand, the writing style is crucial for information comprehensibility and applicability. LPs should be written as step-by-step instructions focusing on activities that the replicating experimenter has to perform. On this ground, we drew up a number of documents detailing the LP structure and further specifying packaging criteria.

Besides the LP template document, we generated a packaging checklist to be used by the researcher instantiating a LP for a specific experiment. The packaging checklist summarizes all the proposed improvements to the structure, content and writing style. The checklist is divided into four different key SE experiment packaging categories:

Instructions for the replicating experimenter
Operational material
Experimental research process support
Structural and usability improvement
The specific components of each improvement are added to the packaging checklist to assure that the research can easily check the instantiated LP. Some of the improvements are already addressed in the modular nature or in specific sections of the LP template.  However, the packaging checklist could be used check and improve the first draft of the LP.

[Packaging checklist document (Microsoft Word format)](./Packaging_checklist.docx)

## Instantiation procedure

To help researchers apply the LP instantiation to different experiments, we generated a LP instantiation procedure. The aim of the procedure is to improve instantiation by providing support for processing the available materials (that may or may not be part of a pre-existing LP), as well as eliciting any tacit knowledge that needs to be specified. Figure 2 outlines the LP instantiation procedure.

![Figure 2](./instproc.png "Figure 2")

The main sources for instantiating a LP are the existing documents related to the experiment and tacit knowledge. The instantiation procedure relies on two tools that are part of the LP proposal: a LP template and a checklist of changes. After a number of intermediate results (restructured documents, list of missing components and new components), the end product is a LP instantiated for a specific experiment.

As any knowledge gathering procedure, the activities don't necessarily occur sequentially. However, starting with the analysis of existing documents and checking the completeness against the proposed LP template, facilitate the identification of tacit knowledge that should be gathered. This activity involves interacting with researchers who may have that knowledge and producing new components for the LP. The checklist of changes is an additional tool for verification of the outcome, and may require redoing previous activities of the procedure.

