# Data Scientist, Software Developer

#### Technical Skills: Python, SQL, AWS, Snowflake, Java, MLOps

## Education				       		
- M.S., Data Science	| RWTH Aachen University, Aachen, Germany (_November 2024_)	 			        		
- B.Tech., Computer Science | SRM University, Chennai, India (_June 2016_)

## Work Experience
**Generative AI Developer (Student Assistant) @ E.ON Energy Research Center (_December 2023 – Present_)**
- Implemented Test Scenarios for Cyber Attack Detection on Power Grid Lines.
- Developed a chain using RAGs to integrate a Large Language Model for generating attack graphs based on Power Grid network infrastructure context from a Neo4j database. Improved the detection pipeline’s performance by replacing the slower MULVAL-based attack detection method, resulting in a significant boost in efficiency.

**Data Engineer @ Munich RE (_April 2023 – October 2023_)**
- Processed, cleansed, and analyzed unstructured cyber insurance data from various clients, identifying and rectifying data quality issues to enhance accuracy and reliability for underwriters and risk assessments.
- Developed Power BI dashboards for internal stakeholders, providing detailed insights and analysis into insurance data.

**Research and Development Engineer @ Dassault Systèmes (_February 2018 – March 2020_)**
- Developed and maintained various components for Dassault’s PLM Tool ENOVIA, including Web UI and backend components.

**Assistant System Engineer @ Tata Consultancy Services (_May 2016 - February 2018_)**
- Java Web Developer for Cross Border Payment Sysem, WorldLink. 

## Projects
### Learning Heuristics for Counting Problems with GNN - Masters Thesis, 2024
[GitLab](https://git.rwth-aachen.de/supreetshm947/anycsp_enum/)

<p align="center">
  <img src="anycsp_grid.gif" alt="grid"><br>
  <em>ANYCSP enumerating 2-coloring solution for an 11 x 11 Grid graph.</em>
</p>


Built on the foundation of [ANYCSP](https://arxiv.org/abs/2208.10227), which addresses Constraint Satisfaction Problems (CSPs) as a decision problem, this work extends its application to counting problems in Graph Coloring and Boolean Satisfiability.

The model introduces a novel Graph Representation called the Constraint Value Graph, which represents input CSP problems and processes them through a Recurrent Graph Neural Network sampling a list of solutions. It is trained through Reinforcement learning on a configurable training distribution that generates random instances.

### CryptoDataPipeline
<p align="center">
  <img src="crypto_app_flow.png" alt="crypto_app"><br>
</p>

Developed a comprehensive data pipeline for acquiring both real-time and historical cryptocurrency pricing data, as well as related Reddit submissions. Orchestrated data collection with Apache Airflow and used PySpark to load data into a Datalake via a Minio Docker Container. Implemented real-time trend analysis by collecting Reddit submissions through Airflow DAGs, storing them in Elasticsearch, and later in Datalake parquet format for sentiment analysis. This ongoing personal project focuses on integrating sentiment analysis with pricing data and plans to incorporate LLMs using Retrieval-Augmented Generation (RAG).

![Bike Study](/assets/img/bike_study.jpeg)

## Talks & Lectures
- Causality: The new science of an old question - GSP Seminar, Fall 2021
- Guest Lecture: Dimensionality Reduction - Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2021
- Guest Lecture: Fourier and Wavelet Transforms - Scientific Computing (PHYS 5315), Fall 2020
- A Brief Introduction to Optimization - GSP Seminar, Fall 2019
- Weeks of Welcome Poster Competition - UTD, Fall 2019
- A Brief Introduction to Networks - GSP Seminar, Spring 2019

- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA)

## Publications
1. Talebi S., Lary D.J., Wijeratne L. OH., and Lary, T. Modeling Autonomic Pupillary Responses from External Stimuli Using Machine Learning (2019). DOI: 10.26717/BJSTR.2019.20.003446
2. Wijeratne, L.O.; Kiv, D.R.; Aker, A.R.; Talebi, S.; Lary, D.J. Using Machine Learning for the Calibration of Airborne Particulate Sensors. Sensors 2020, 20, 99.
3. Lary, D.J.; Schaefer, D.; Waczak, J.; Aker, A.; Barbosa, A.; Wijeratne, L.O.H.; Talebi, S.; Fernando, B.; Sadler, J.; Lary, T.; Lary, M.D. Autonomous Learning of New Environments with a Robotic Team Employing Hyper-Spectral Remote Sensing, Comprehensive In-Situ Sensing and Machine Learning. Sensors 2021, 21, 2240. https://doi.org/10.3390/s21062240
4. Zhang, Y.; Wijeratne, L.O.H.; Talebi, S.; Lary, D.J. Machine Learning for Light Sensor Calibration. Sensors 2021, 21, 6259. https://doi.org/10.3390/s21186259
5. Talebi, S.; Waczak, J.; Fernando, B.; Sridhar, A.; Lary, D.J. Data-Driven EEG Band Discovery with Decision Trees. Preprints 2022, 2022030145 (doi: 10.20944/preprints202203.0145.v1).
6. Fernando, B.A.; Sridhar, A.; Talebi, S.; Waczak, J.; Lary, D.J. Unsupervised Blink Detection Using Eye Aspect Ratio Values. Preprints 2022, 2022030200 (doi: 10.20944/preprints202203.0200.v1).
7. Talebi, S. et al. Decoding Physical and Cognitive Impacts of PM Concentrations at Ultra-fine Scales, 29 March 2022, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-1499191/v1]
8. Lary, D.J. et al. (2022). Machine Learning, Big Data, and Spatial Tools: A Combination to Reveal Complex Facts That Impact Environmental Health. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_12



Foundations of Supervised ML with Graphs - Seminar (https://github.com/supreetshm947/Seminar_report_ESAN), 2022
Wrote a report on paper Equivariant Subgraph Aggregation Networks which works upon the limitation of Weisfeiler-Leman (WL) Test that is unable to distinguish simple graphs and presents a novel and more expressive method.

9. Wijerante, L.O.H. et al. (2022). Advancement in Airborne Particulate Estimation Using Machine Learning. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_13

- [Data Science Blog](https://medium.com/@shawhin)
