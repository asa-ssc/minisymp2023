---
layout: page-fullwidth
title: "Program"
header: no
permalink: /program/
---

## Schedule

All times are in the [Central Time Zone](https://en.wikipedia.org/wiki/Central_Time_Zone).

+ 11:00 – 11:10: Welcoming Remark (Chair: [David Dahl](https://dahl.byu.edu/), Brigham Young University)
    - [Ron Wasserstein](https://www.amstat.org/about-asa/ronald-l-wasserstein),
	Executive Director, [American Statistical Association](https://www.amstat.org/)
    - [Mine Çetinkaya-Rundel](https://scholars.duke.edu/person/mine), Professor
      of the Practice and the Director of Undergraduate Studies at the
      [Department of Statistical Science](https://stat.duke.edu/), [Duke University](https://duke.edu/); 
	    and 2023 Chair of the ASA Section on Statistical Computing
+ 11:10 – 11:50: Keynote Address (Chair: [Mingzhao Hu](https://sites.google.com/view/mingzhaohu))
    - Speaker: [Simon Urbanek](https://urbanek.info),
	      - Executive Editor of R Journal;
	      - Senior Lecturer of Data Science, University of Auckland
    - Title: R in Big Action: Handling large data sets and R as a service
+ 11:50 – 13:05: Data Jamboree (Chair: [Sam Tyner](https://sctyner.me), DLA Piper)
    Each language, in alphabetical order, will be allocated 15 minutes to tackle
    the same problems from the NYC 311 requests data, followed by questions/answers.
    - Python: [Shannon Tass](https://neeley-tass.byu.edu), Associate Professor, 
      Department of Statistics, Brigham Young University. [Code](https://github.com/esnt/Jamboree)
    - Julia: [HaiYing Wang](https://ossifragus.github.io), Associate Professor,
      Department of Statistics, University of Connecticut. [Code](https://github.com/Ossifragus/DataJamboree)
    - R: [Lucy D'Agostino McGowan](https://www.lucymcgowan.com/about/), 
	Assistant Professor, Department of Statistical Sciences,  Wake
	Forest University. [Code](https://github.com/LucyMcGowan/2023-data-jamboree)
+ 13:10 - 14:25: Lightning Session (Chair: [Kun Chen](https://kun-chen.uconn.edu), University of Connecticut)
    <!-- - Abstract submission deadline: Monday, October 2, 2023 -->
    <!-- - Notification: Accepted abstracts will be notified by Monday, October 16, 2023 -->
    <!-- - Submit your abstract [here](https://forms.gle/5ZYbePJtAnsqXqhN7) -->
    - Bowei Xi, Purdue University
	<details><summary>Title:Vulnerabilities of Deep Learning and Robust Deep
	Ensemble</summary>
	Although AI is developing rapidly, AI's vulnerability under adversarial
	attacks remains an extraordinarily difficult problem. We discuss the root
	cause of adversarial examples through studying the deep neural network's
	(DNN) classification boundary. The existing attack algorithms can generate
	from a handful to a few hundred adversarial examples given one clean
	sample. We show  there are a lot more adversarial examples given one clean
	sample, all within a small neighborhood of the clean sample. We then define
	DNN uncertainty regions and show the transferability of adversarial examples
	is not universal. The results lead to two conjectures regarding the size of
	the DNN uncertainty regions and where DNN function becomes
	discontinuous. The conjectures offer a potential explanation for why the
	generalization error bound -- the theoretical guarantee established for DNN
	-- cannot adequately capture the phenomenon of adversarial examples. We then
	introduce a deep ensemble with high accuracy over the adversarial examples.
	</details>
    - Howard Baek, Fred Hutch Data Science Lab
	<details><summary>Introducing Loqui: A Shiny app for Creating Automated
	Videos</summary>
	Loqui is an open source web application that enables the creation of
	automated videos using ari, an R package for generating videos from text and
	images. Loqui takes as input either a Google Slides URL or a Microsoft
	PowerPoint file, extracts the speaker notes from the slides, and converts
	them into an audio file. Then, it converts the slides to images and
	ultimately, generates an mp4 video file where each image is presented with
	its corresponding audio. The functionality of Loqui relies on two R
	packages, namely ari and text2speech, which run in the background. Although
	it is certainly possible to go directly to these packages and run their
	functions for course generation, we realize that not everyone feels
	comfortable programming in R. This web application offers an intuitive and
	user-friendly interface allowing individuals to effortlessly create
	automated videos without the need for programming skills.
	</details>
    - Kris Sankaran, University of Wisconsin-Madison
	<details><summary>Beyond Black Box Simulation</summary>
	Simulation models have come to play a central role both within and beyond
	statistics, providing the basis for power analysis in molecular biology,
	theory building in particle physics, and resource allocation in
	epidemiology, for example. We will highlight points of contact between
	statistics and simulation, with an emphasis on how careful interface design
	can make simulators more transparent both to the scientists who build them
	and the broader audiences that must draw conclusions from them. We overview
	approaches to iterative, interactive simulation design and visualization of
	simulation outputs in an information-dense way. We will illustrate these
	strategies using examples from experimental design, mixture modeling, and
	agent-based simulation. Further examples can be found in the recent review,
	[“Generative Models: An Interdisciplinary
	Perspective”](https://doi.org/10.1146/annurev-statistics-033121-110134)  and
	code notebooks be accessed
	[online](https://github.com/krisrs1128/generative_review).
	</details>
    - Zoe Rehnberg and Emily Robinson, California Polytechnic State University
	<details><summary>Enhancing Statistical Computing Education through Game
	Plans: A Pedagogical Approach</summary>
	In statistical computing education, students often grapple with the
	transition from conceptualizing a data task, such as data wrangling or
	visualization, to writing the necessary code. While students likely have the
	original data set and a vision of the desired outcome, we need to teach
	students how to translate a general task (e.g., add a variable, combine two
	data sets, summarize groups, create a visualization, etc.) into appropriate
	(and correctly ordered) lines of code. Further, as tasks get more
	complicated and datasets get larger, this translation between the data task
	and code becomes increasingly difficult. Drawing from computer science
	education literature, which advocates breaking down steps of complex
	problem-solving tasks and writing about code (Catrambone, 2011), we
	introduced “game planning” into four sections of introductory statistical
	computing that focus on the tidyverse in R. Game plans serve as strategic
	guides that prompt students to map their coding strategies before
	implementation. Students can create game plans in various formats, such as
	pen-and-paper or digital tools like the online whiteboard Excalidraw. Our
	presentation explores the rationale behind game plans, showcases diverse
	student approaches, and provides practical tools and examples, all aimed at
	improving students’ proficiency and structured thinking in statistical
	computing.
	</details>
    - Jonathan Sidi, Sage Therapeutics
	<details><summary>mmrm: a robust and comprehensive R package for
	implementing mixed models for repeated measures</summary>
	Mixed models for repeated measures (MMRM) analysis has been extensively used
	in the pharmaceutical industry to analyze longitudinal datasets. SAS PROC
	MIXED has been the gold standard for this analysis in the past, and so far R
	packages fall short for one of the following reasons: model convergence
	issues, unavailability of covariance structures or adjusted degrees of
	freedom, or numerical results being far from PROC MIXED results. To fill in
	this important gap in the open-source statistical software landscape,
	cross-company collaboration via the “Software Engineering Working Group”
	(SWE WG) has been initiated and developed the new {mmrm} R package. A
	critical advantage of {mmrm} over existing implementations is that it is
	faster and converges more reliably. It also provides a comprehensive set of
	features: users can specify a variety of covariance matrices, weight
	observations, fit models with restricted or standard maximum likelihood
	inference, perform hypothesis testing with Satterthwaite or Kenward-Roger
	adjusted degrees of freedom, extract the least square means estimates using
	the emmeans package, summarize with the broom package and integrate with the
	tidymodels framework. We aim to establish {mmrm} as a new standard for
	fitting MMRM.
	</details>
    - Shane Sacco, University of Connecticut
	<details><summary>Tips and tricks to improve the speed of your prediction
	pipelines and other analyses</summary>
	Statistical analysis on large datasets may take days or even weeks to
	complete, costing us valuable time and essentially halting the progress of a
	project. While in some cases, there is little we can do, in many cases,
	there are methods available to speed up computationally expensive
	tasks. Especially when executing a prediction pipeline, there are many of
	such tasks including cohort processing, marginal screening, model training,
	and repeating the experiment. In this presentation, I will provide tips and
	tricks to reduce the time required for tasks across various stages of the
	prediction pipeline, which also generalize to other types of analyses. I
	will focus on analyses in R, but will also make suggestions for Python when
	appropriate.
	</details>
    - David Corliss, Peace-Work
	<details><summary>Designing Against Bias in Machine Learning and
	AI</summary>
	Bias in machine learning algorithms is one of the most important ethical and
	operational issues in statistical computing today. This presentation
	describes common sources of bias and how to design and develop algorithms
	that mitigate them. Analysis of disparate impact is used to quantify bias in
	existing and new applications. New open-source packages such as Fairlearn
	and AI Fairness 360 Toolkit quantify bias by automating the measurement of
	disparate impact on marginalized groups, offering great promise to advance
	the mitigation of bias. These design strategies are described in detail with
	examples and source code in R, Python, and SAS.
	</details>
    - Yulia Marchenko, StataCorp LLC
	<details><summary>Software reproducibility in a nutshell</summary>
		Reproducibility of scientific studies has been gaining increasing
	attention in recent years. But what exactly is reproducibility? How is it
	related to replication, repetition, and automation? When can we achieve
	reproducibility and to what degree? How can we incorporate reproducibility
	in our data analysis? And what role does software play for reproducibility?
	In this presentation, I will briefly address these questions and more.
	</details>
    - Arinjita Bhattacharyya, Merck
	<details><summary>AACTREVEAL – An R Package for Analysis and Aggregation of
	the Content of ClinicalTrials.gov</summary>
	Aggregate Content of ClinicalTrials.gov (AACT) is a publicly available
	database that contains a variety of trial-level information for every study
	registered in ClinicalTrials.gov. Content is downloaded from
	ClinicalTrials.gov daily and loaded into AACT. This research work introduces
	the open source aactreveal R package, which provides functions for
	consolidating analysis datasets from AACT and conducting meta-analyses using
	the analysis datasets. The main function, extract_aact() conducts a
	comprehensive search of clinical trials by looking for related search terms
	(e.g., “pembrolizumab” or “breast cancer”) and utilizing fuzzy string
	searching. Then, it fetches the desired outcome data such as treatment
	effect estimates, confidence intervals, and variance estimates. An R package
	is also developed, for public use. Although the demo of the package will
	focus on oncology trials, the package makes it easier for statisticians to
	explore AACT in other respective therapeutic areas. It is available publicly
	at https://github.com/Merck/bards-aactreveal.
	</details>
+ 14:30 - 15:30: Panel Discussion (Moderator: [David Dahl](https://dahl.byu.edu))
    - Theme: Open-source software, open data, and open computing
    - Panelist:
        + [Tracy Teal](https://www.linkedin.com/in/tracy-teal-059136b/)
            - Open Source Program Director, Posit PBC
        + [Carol Willing](https://www.willingconsulting.com/about/)
            - Python and Jupyter Core Developer, VP of Engineering, Noteable
        + [Achim Zeileis](https://www.zeileis.org)
            - Editor-in-Chief of Journal of Statistical Software
            - Professor, Universität Innsbruck
