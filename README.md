# Contributed session: Developing, administering and refining measurement instruments in Social Sciences
Proponents: Ottavia M. Epifania, Pasquale Anselmi

Chair & Discussant: Livio Finos

## [Overview](general/contributed-session-asa2024.pdf) 

The need for valid and reliable measurement instruments in Social Sciences is well established, also for the sake of the replicability of the results. This contributed session presents three contributions where the development, administration, and refinement of measurement instruments in Social Sciences are tackled under different perspectives. Specifically, the first contribution is about the development and validation of a new measurement tool for assessing soft skills using Knowledge Space Theory (KST). The second contribution describes the advantages provided by KST for the efficient administration of a test in a computerized adaptive testing (CAT) instance. Finally, the last contribution focuses on a different perspective, namely Item Response Theory, and presents a new algorithm for the intelligent selection of items from an item bank for the development of short questionnaires with specific characteristics defined by test developers. A final discussion on the usefulness of these and related approaches for the social sciences conclude the contributed session. 

The session will be held on September 19, 2024 in Room 1 (Gini) at 4:00pm. The full conference program is available [here](https://cess2022.dss.uniroma1.it/event/10/attachments/118/413/PROGRAMME%20ASA2024%20CONFERENCE%20ver%202%2009rev.pdf)

## Contributions: 

### [*Design of a test for assessing teamwork and collaborative skills with Competence-based Knowledge Space Theory*](/morleo/morleo-asa.pdf)

**Federica Morleo**, Alessandra Vitanza, Pasquale Anselmi 

A critical issue within the educational system is the availability of assessment tools capable of accurately describing the skills mastered by an individual and those that are not. Competence-based Knowledge Space Theory (CbKST) is a mathematical theory for the individual assessment of skills that aims to precisely identify the set of skills an individual possesses within a specific domain based on responses given to the items of a test. CbKST is an extension of Knowledge Space Theory (KST), in which the main difference refers to the latent variable considered. While KST focuses on the items an individual is capable of solving, CbKST emphasizes the skills mastered by the individual that allow him to solve these items. CbKST provides the theoretical framework for this work, which presents the development and validation of a tool for the assessment of teamwork and collaborative skills (e.g., effective communication, conflict resolution, action planning, performance monitoring, and feedback) in nursery and primary schoolteachers. The test was designed to offer an attractive user-experience on a web-based platform that simulates real-life situations, such as exchanging messages in a chat with colleagues or viewing students’ work. Data collected on a sample of more than one hundred teachers coming from public and private schools in Italy are analyzed and discussed.

### [*An R Package for Adaptive Assessment Utilizing Knowledge Space Theory and Formal Psychological Assessment*](/brancaccio/brancaccio.pdf) 

**Andrea Brancaccio**, Umberto Granziol 


Adaptive assessment techniques are crucial in educational and psychological testing because of their ability to tailor evaluations to individual needs. This presentation introduces a novel R package, Adaptive Assessment Tool, which implements procedures from Knowledge Space Theory and Formal Psychological Assessment to perform adaptive assessments. The package is complemented by an R Shiny interface, which makes it accessible and user-friendly for practitioners.
The R package offers several key functionalities, including performance simulation and adaptive test administration. It allows the evaluation of the efficiency and accuracy of the assessment procedure by the simulation of response patterns. The results of these simulations allow fine-tuning of assessment parameters, such as the termination criterion, to prioritize either efficiency or accuracy, depending on the application.
The Shiny interface has a dual purpose. First, it simplifies the implementation of the assessment, allowing users (e.g. teachers or clinicians) to build the knowledge space and interactively monitor the assessment process in real-time. Second, it serves as a field support tool for adaptive assessment administration, providing users with comprehensive reports of the assessment output.
In general, this R package and Shiny interface present a powerful and flexible tool for adaptive assessments to create individualized testing experiences. The included simulation capabilities also enable practitioners to evaluate and refine their assessment instruments, ultimately leading to a more effective assessment.


### [*Test length doesn't matter, it's how you use the items that counts: An intelligent procedure for item selection in Item Response Theory*](/epifania/presentazione/ila-asa2024.pdf) 

**[Ottavia M. Epifania](https://ottaviae.github.io/presentations/)**, Pasquale Anselmi, Egidio Robusto
 
Item Response Theory (IRT) provides the ideal framework for generating short test forms (STFs) from item banks or from full-length tests thanks to the possibility of obtaining detailed information on the precision with which each item measures the latent trait. As such, the most precise items can be selected for inclusion in the STF and the number of items can be minimized while the measurement precision can be maximized. The usual procedure for developing STFs is based on the visual inspection of the item and test information functions (IIFs and TIFs) to find the items that best contribute to make up a STF with the desired characteristics. This contribution presents a new procedure that aims at automating this process by defining a target TIF and finding the items from the item bank that best recover it. The algorithm directly compares the distance between the target TIF and a temporary TIF obtained by adding an item at a time. The items are chosen according to their closeness to the location on the latent trait where the distance between the target and the temporary TIFs is maximized. The algorithm stops when the addition of a new item does not reduce the distance between target and temporary TIFs. The procedure can be applied both when the length of the STF is defined a priori and when the aim is to find the optimal number of items. The results of the application of this procedure are presented. 

## The speakers

### Federica Morleo 

Fedrica is a PhD Student in Social Sciences, curriculum Applied Psychology at the University of Padova, associated with the National Research Council. Her current research interests are focused on the development of new pedagogical approaches, based on the use of educational robotics and emerging technologies.

### Andrea Brancaccio

Andrea is a researcher at the National Research Council, currently employed on the RAISE Liguria project. His research focuses on assessment and learning models for education and clinical settings.


### Ottavia M. Epifania

Ottavia is a tenure-track researcher at the University of Trento. Her research focuses primarily on Item Response Theory models and their use to improve and shorten tests and questionnaires used in research and clinical settings
