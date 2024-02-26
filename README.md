    Hackathon on digital pharmacology. Toxic Girls comand's Solution
In this hackathon (https://medtech.moscow/news/211), the organizers set a goal in 48 hours to develop a model that predicts the toxicity of chemical compounds using ML and DL models.
Our model predicts the most commonly used toxicological characterization, the semi-lethal dose (LD50), given the route of administration of the drug (i.p., i.v., orally, and s.c.), as well as hepatotoxicity. 11 datasets (Datasets folder) with about 35,000 unique molecules were independently collected from open sources, cleaned and processed, descriptors describing the structure of each molecule were extracted from them. The values obtained from the databases had units of mg/kg. To bring them to a convenient form, we converted them to mol/kg and took the inverse decimal logarithm from them.
They tested classification and regression models of machine learning, as well as measured quality metrics. Everything was designed into a single pipeline (Main_Pipeline). The tests were conducted by Syntelly on a closed test set, focusing on their benchmarks. My role in the team was to build the work of the team (I was the captain), find the optimal machine learning model, I also found and processed some of the original datasets on my own, bringing them to a working state, as well as helping to write the final pipeline. As a result, we entered the final, in the top 27 teams (7%) at the end of the competition (there were 80 teams in total, 379 participants)



Muravetskii Daniil, Moscow Institute of Physics and Technology,
May 2023
