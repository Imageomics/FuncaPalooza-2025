# FuncaPalooza 2025 - Call for Participation

## Synopsis

The Imageomics Institute is hosting a 3.5-day workshop offering a unique opportunity to develop proof-of-concepts demonstrating how the application of computer vision techniques can transform functional trait data extraction and analysis from images. The event will bring together an interdisciplinary group around a shared interest of using AI/ML to extract functional traits from imagery, including ML researchers, ecologists, biologists, software developers, and data engineers. Participants will work in small groups to collaboratively curate or develop [FAIR](https://www.go-fair.org/fair-principles/) data products, best practices, tools, workflows, and other products targeting the motivating challenge.

The event will take place August 18-21 at The Ohio State University in Columbus, OH, USA. To apply to participate, please fill out the [FuncaPalooza 2025 Application for Participation](https://forms.gle/PaL27To4AP41KMJB6) by the end of June 23, 2025. Funds to assist with travel expenses are available but limited, as is space. We expect to notify applicants about acceptance by July 7, 2025.

## About the event

FuncaPalooza 2025 will bring together an interdisciplinary group interested in using AI/ML to extract functional traits from image data. Traits derivable from images might include, but are not limited to, morphological attributes (e.g., beak shape, coloration, or patterning), phenological traits (e.g., timing of flowering, leaf-out dates), or trophic characteristics (e.g., diet type). This event offers a hands-on, collaborative experience. It is not intended to be a competitive hackathon or a conference. We expect participants to include AI/ML researchers, data scientists, ecologists, evolutionary biologists, data or specimen curators, tool developers, and knowledge engineers. Participants will self-organize into small groups to work hands-on and collaboratively on self-selected targets and outcomes towards the motivations and goals of the event. The process of self-organizing and choosing work targets will be facilitated, but every participant will play an equally active role in making the event a successful, rewarding experience. We aim for an event that will give everyone ample opportunities to contribute their skills and experience, acquire new knowledge, increase technological awareness, and find potential new collaborators. Although the event is primarily designed to create code, datasets, workflows and other tangible outcomes, the format will leave room for networking and participant-driven exchange of know-how and skills.

## Motivation

Functional traits, measurable features of organisms related to their ecological roles, are crucial in ecology for understanding how species interact with their environment, contribute to ecosystem processes, and respond to environmental changes. Functional traits may be morphological (e.g., size; [Grant et al. 2008](https://academic.oup.com/biolinnean/article-abstract/25/1/1/2670648)), biochemical (e.g., the amount of nitrogen in a leaf; [Wright et al. 2004](https://www.nature.com/articles/nature02403)), physiological (e.g., body size; [Brown et al. 2004](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/03-9000)), phenological (e.g., flowering; [Ramirez-Parada et al. 2024](https://www.nature.com/articles/s41559-023-02304-5)), or behavioral (e.g., personality; [Merz & Mortelliti 2024](https://nsojournals.onlinelibrary.wiley.com/doi/full/10.1111/oik.10583)) characteristics that are expressed by phenotypes of individual organisms. In this workshop, we ask can we get functional traits from images? 

We will approach this question with recently developed AI/ML tools. For example, the Imageomics Institute has developed a variety of tools and ML models for extracting various morphological aspects from images, including:

* [BioCLIP 2](https://imageomics.github.io/bioclip-2/): a foundation model for the tree of life with a vast set of emerging properties  
* Landmarking and segmentation ([SST](https://github.com/Imageomics/SST), [wing-segmentation](https://github.com/Imageomics/wing-segmentation))  
* Morphology measurements (LepidopteraLens)  
* Fine-grain image analysis and interpretability ([Prompt-CAM](https://github.com/Imageomics/Prompt_CAM), [Finer-CAM](https://github.com/Imageomics/Finer-CAM), [INTR](https://github.com/Imageomics/INTR))  
* Connections to taxonomy and phylogeny ([HComP-Net](https://imageomics.github.io/HComPNet/), [Phylo-Diffusion](https://imageomics.github.io/phylo-diffusion/))  
* Bring your own!

We hope workshop participants will bring data to work with, questions that may be answered about functional traits, and/or ML tools for quantifying functional traits from images. Most of all, we ask participants to bring their enthusiasm for and curiosity about applying AI/ML tools to explore questions relating to morphological traits and biological discovery!

### Goals/Desired Outcomes

We aim to facilitate outcomes that address the potential of and need for ML-ready biological image datasets and workflows to extract information about functional traits, including (but not limited to!) the following:

* Taxa-based prototype workflows (e.g., for beetles, butterflies, birds, plants, fish) for extracting morphological traits from images that are reproducible, follow FAIR guiding principles, and are understandable/usable by biologists and computer scientists.  
* Publication of open data products containing species identifications and functional morphological traits derived from images.  
* A peer-reviewed publication describing best practices for extracting morphological traits from images and feeding into AI/ML.  
* [FAIR](https://www.go-fair.org/fair-principles/)/[CARE](https://www.gida-global.org/care)\-adhering and ML-ready datasets, including in particular image and video datasets suitable for answering functional trait-based questions. Ideally, these would be paired with a model or benchmarking results.

### Scope

We are keeping the scope of possible projects focused on functional trait-based exploration (morphological traits that are visible in images or video) to maximize the limited time of the workshop. That notwithstanding, we expect the event to connect people with biological science-focused goals. For instance biologists interested in asking biological questions with AI/ML tools or AI/ML researchers interested in ecological or evolutionary questions for which to develop algorithms and models.

We generally expect datasets curated at or for the event, as well as tools or methods developed, to satisfy [FAIR principles](https://www.go-fair.org/fair-principles/), and where applicable also [CARE principles](https://doi.org/10.1038/s41597-021-00892-0). For those bringing datasets, we will reach out ahead of the event to help ensure their readiness for question-answering. Here are some examples of curated datasets on [beetles](https://huggingface.co/datasets/imageomics/2018-NEON-beetles), [fish](https://huggingface.co/datasets/imageomics/fish-vista).

### Date and Location

The event will be held August 18-21, 2025, at the Imageomics Institute’s headquarters at The Ohio State University, [Pomerene Hall](https://tdai.osu.edu/pomerene-hall), in Columbus, OH.

## Who should participate

We aim to bring together a diverse group of people, including AI and ML researchers and practitioners, ecologists and biologists, as well as related domain scientists, information scientists, software developers, ontologists, and data or specimen curators. Members of organizations in the US National Science Foundation (NSF) funded Harnessing the Data Revolution ([HDR](https://www.nsf.gov/cise/harnessingdata/)) ecosystem are particularly encouraged to consider applying, including members of their respective computer science and domain science stakeholder communities. For example, for the Imageomics Institute, this includes computer scientists working on AI/ML for images, text, and video, and biologists interested in using image and video data at large scale to answer trait-based biological questions.

In general, people encouraged to consider applying include (but are not limited to!) the following:

* AI/ML experts and researchers, particularly those in computer vision (CV), interested in collaboratively advancing tools, infrastructure, and data products that are domain science-enabling.  
* Ecologists (and related domain scientists such as biodiversity and environmental scientists) who are interdisciplinary-minded and ideally have already used or are planning to use image data in their research, and/or have some familiarity with applying ML and computer vision for ecological research questions.  
* Researchers with large image-based datasets who are interested in using ML to answer questions related to functional traits.  
* Software engineers or programmers with skills requisite for AI/ML (Python and applicable libraries, etc.), data wrangling/management (SQL, Pandas, R, etc.) who are interested in developing automated ML workflows, tools and infrastructure.  
* Data engineers with experience and expertise in creating FAIR data products suitable for AI/ML applications.  
* Graduate students and postdocs looking for an opportunity to develop their skills in interdisciplinary research at the intersection of AI/ML and domain science (ecology, biodiversity and environmental science).  
* Advanced undergraduates in computational biology, computer science (ML/CV), math, or data analytics with demonstrated interest in interdisciplinary research.

Everyone participating in the event must adhere to its [Code of Conduct](https://github.com/Imageomics/FuncaPalooza-2025/blob/main/CODE_OF_CONDUCT.md).

## About the Imageomics Institute

The [Imageomics Institute](https://imageomics.org/) is funded by the US National Science Foundation (NSF) within its [Harnessing the Data Revolution (HDR) Institute](https://new.nsf.gov/funding/opportunities/harnessing-data-revolution-institutes-data/505828/nsf21-519/solicitation) program. The Institute has been focused on creating a collaborative research, training, and community-facing environment for extracting known and discovering new biological traits from images, with the necessary infrastructure for cyber, information, and model development. The Institute will advance Imageomics-enabled biology, accelerate innovations in machine learning, and create digital resources for the researchers and practitioners in biology, data science, and machine learning, as well as the broader scientific community. It will further interdisciplinary training and education, and engage the broader public in the scientific process. Accomplishing these tasks will provide unique insights and enable biological discovery over a wide range of informative organismal attributes&mdash;some not yet comprehended or studied&mdash;and across multiple scales of biological organization from individuals to species.

## Organizing Team

* [Elizabeth Campolongo](https://egrace479.github.io/) (The Ohio State University & Imageomics Institute)  
* [Alyson East](https://aeastecology.wixsite.com/website) (University of Maine)  
* [Marta Jarzyna](https://www.jarzynalab.com/) (The Ohio State University)  
* [Hilmar Lapp](https://orcid.org/0000-0001-9107-0714) (Duke University & Imageomics Institute)  
* [Sydne Record](https://sites.google.com/maine.edu/record-lab) (University of Maine)
