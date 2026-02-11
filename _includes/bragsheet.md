# Fable Therapeutics - ML Operations Lead (2024 - present)

* Re-architected Fable's design-generation pipeline from 27 manually chained Jupyter notebooks into a config-driven Python orchestration system on AWS Batch (auto-queueing, compute routing, spot fleets, centralized observability via CloudWatch).
* Reduced per-run operator time from ~2 weeks of manual coordination to ~8 hours through full automation and standardized failure handling.
* Cut recurring compute cost ~60% per run ($130k-$170k -> $50k-$60k) for a biweekly production pipeline by improving resource utilization and instance selection.
* Chose an incremental rollout over a full EKS/Kubernetes replatform, preserving existing workflows while achieving immediate adoption across all 8 production users.
* Built CI/CD across internal repos and model pipelines using GitHub Actions, enforcing lint/test/build gates, automated Docker builds/deployments, and standardized release workflows.
* Established code quality standards and review operating model (PR templates, review guides, required checks/reviewers), then drove adoption through coaching and documentation across a 9-person team.
* Integrated Weights & Biases artifact/version tracking into the model release workflow, enabling PR-based config changes with full model lineage and reproducibility.
* Reduced required manual interventions during production batch runs by ~70% year-over-year by automating orchestration and eliminating common failure points in the pipeline.
* Reduced inference unit cost by >99% (~$1 -> <$0.01 per prediction) across >90% of production workloads through input pruning, custom kernels, and optimized GPU selection, while maintaining equivalent output quality.
* Reduced training compute from ~1,920 to ~80 H100 GPU-hours by removing CUDA sync bottlenecks, using compiled PyTorch, and adding optimized CUDA kernels, with no model quality loss.
* In a representative 180-day period: contributed 52/152 merged PRs, completed 78/228 PR reviews, authored 491/1200 commits, and reviewed ~120k LOC across a 9-person engineering team.

# Semantic Health (acquired) - ML Lead (2021 - 2022)

* Spearheaded the research and development of the company's clinical ML offerings (variety of clinical NLP + OCR + Tabular), successfully delivering multiple client deployments, leading to a US expansion, and driving a $60M valuation.
* Hired and led a team of 7 ML Scientist / Engineers: Managed their professional growth, setting objectives, conducting standups, and nurturing their leadership and technical capabilities.
* Defined Hiring Policies and Interview Processes: Established effective hiring policies, interview questions, scoring systems, and take-home assignments to identify top talent for ML, Data Engineering, and Backend roles.
* Created the long-term ML product vision of the company
* Rewrote the initial Python stack reducing technical debt and allowing for new hire onboarding without big issues. Introduced unified code, data, and testing standards
* Created and deployed multiple new ML product lines based on customer calls and product insights from internal QA efforts leading to increases of 100k ARR per contract
* Introduced a novel non-intrusive data labelling and feedback scheme, increasing the granularity of labels without impacting the end user's workflow, which led to creation of new models with >50\% performance gain on downstream KPIs
* Created weekly progress reports and presented at all-hands and led customer calls
* Created extensive model and prediction fallbacks allowing us to eliminate the need for on-call support on the ML side
* Contributed to open-source libraries supporting US Military veteran care efforts. Named the first outside collaborator to the library.
* Contributed optimizations to multiple NLP libraries allowing for parallelization of computation (spaCy extensions + Srsly)
* Supervised research projects leading to multiple scientific publications and product improvements
* Created an active learning approach allowing to improve data labelling efforts reducing costs by >75% 
* Led the MLOps + DevOps efforts to integrate ML into dev and staging cloud environments allowing for end-to-end model testing for releases which allowed the team to move away from on-prem testing
* Led code review and tech debt improvement sprints across the entire Python stack
* Designed and implemented APIs for vending model predictions
* Roadmapped and oversaw a new MLOps initiative to allow for better data and model monitoring (Feast + MLflow + Seldon)
* Led internal R&D efforts on new modelling schemes to improve the existing products

# UofT - Teaching (2020 - 2023)

* Developed comprehensive educational materials and delivered engaging instruction for a range of undergraduate and graduate courses in Statistics and Machine Learning.
* Communicated sophisticated technical topics to a non-technical audience
* Modernized the CSC412 - Probabilistic ML course curriculum by adding Attention, Transformers, and Diffusion models

# Semantic Health - Machine Learning Scientist (2019 - 2020)

* Joined as the first employee - architected and built the ML stack setting the foundation for the company's NLP capabilities
* Developed Transformer-based models consistently surpassing the state-of-the-art performance on a complex, massively multi-label dataset with significant labeling noise.
* Successfully deployed models to production, initially through Python scripts and database uploads, later optimizing the process by transitioning to Airflow, leading to first long-term customer contracts
* Designed and implemented a diverse stack of models, spanning from basic keyword matching to advanced Deep Learning techniques.
* Pioneered a novel architecture for generating supporting evidence for ML model predictions, implemented and deployed it leading to a 300% increase in business KPIs for the product
* Developed a custom multi-armed bandit model deployment scheme eliminating guesswork and quadrupling ML deployment velocity to production (monthly to weekly model release cadence)
* Engaged with customers and gathered feedback to iterate on model improvements, ensuring alignment with customer needs and expectations.
* Conducted ML feature discovery calls with end users, resulting in the development of simple ML models that significantly enhanced product performance
* Established a custom quality assurance process for on-premises model deployments in a secure environment, guaranteeing model reliability and performance.
* Authored a series of Architecture Decision Records that still serve as the model for decision documents for the company
* Actively contributed to the company's culture by hosting weekly game sessions and fostering a positive and engaging atmosphere in meetings.
* Implemented a comprehensive testing suite for the ML stack, including model minification allowing for pre-commit end-to-end ML testing
* Planned and conducted data and label quality experiments identifying problems, addressed those by creating a novel, ontology-graph based label smoothing algorithm increasing model performance by 35%
* Found and solved a major bug in a huge open-source framework (AllenNLP)

# UofT - Masters (2019 - 2022)

* Part-time masters while working a full-time (early stage startup) job
* An average (only one course not A+) in challenging courses
* Actively engaged in research leading to Publications and a Research Visitor position at St. Michael's Hospital in Toronto
* Recognized for expertise, was offered to teach my own cohort as a sessional lecturer in Machine Learning

# UofT - Bachelors (2015 - 2019)

* President Stats Union - brought it from a dead union (won with 14 total votes for a president of a union with ~6000 members) to multiple yearly events with attendance in the hundreds
* Took on teaching assistant (TA) responsibilities for upper-level courses while still an undergraduate, including instructing students in my own year.
* 4.0 GPA in stats courses
* Allowed to take One-on-One reading courses under famous professors (Dan Simpson, David Duvenaud)
* Actuarial Students National Association (ASNA) leadership from second year - held Director positions for Operations, Events, and Case competition
* Conducted ML research at RiskLab

# Deloitte (2018)

* Authored a practice-wide internal report on the state and future of AI in insurance
* Participated in reserving audits for a number of large auto insurance customers
* Assumed a client-facing role by working on-site for nearly 8 months, collaborating closely with a major auto-insurance client to fulfill their data engineering needs, assisting in reconciling their extensive book of business.
* Contributed to creation of a report for the Ministry of Finance on the state of Auto Insurance in Canada

# Intact (2017)

* First year intern building a relatively large data project on my own (EoE)
* Built GLM auto insurance pricing models for regulators

# Family business (2023)

* Built an English version of the site (WP)
* Done Business dev efforts to expand the company to North America

# Misc

* Podcast guest for the Mentorship podcast
  
