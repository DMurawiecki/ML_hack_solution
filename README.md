    Хакатон по цифровой фармакологии. Решение Toxic Girls
В данном хакатоне (https://medtech.moscow/news/211) организаторами была поставлена цель за 48 часов разработать модель, предсказывающую токсичность химических соединений с помощью ML и DL моделей.
Наша модель предсказывает наиболее часто используемую токсикологическую характеристику – полулетальную дозу (LD50), с учетом способа введения препарата (внутрибрюшинно, внутривенно, орально и подкожно), а также такой показатель как гепатотоксичность. Были самостоятельно собраны из открытых источников, очищены и обработаны 11 датасетов (папка Datasets) с порядка 35000 уникальных молекул, выделены из них дескрипторы, описывающие строение каждой молекулы. Полученные из баз данных значения имели единицы измерения мг/кг. Для приведения их к удобному виду, мы провели конвертацию в моль/кг и взяли от них обратный десятичный логарифм.
На них были протестированы классификационные и регрессионные модели машинного обучения, а также померены метрики качества. Всё было сконструировано в единый пайплайн (Main_Pipeline). Тесты проводила компания Syntelly на закрытом тестовом наборе, ориентируясь на свои бенчмарки. Моя роль в команде заключалась в построении работы команды (я был капитаном), нахождении оптимальной модели машинного обучения, также часть оригинальных датасетов я самостоятельно нашёл и обработал, доведя до работающего состояния, а также помощь в написании итогового пайплайна. В качестве результата мы вошли в финал, в 27 лучших команд (30%) по итогу соревнования (всего команд было 80, 379 участников)



Муравецкий Даниил, МФТИ,
май 2023 г.





    Hackathon on digital pharmacology. Toxic Girl's Solution
In this hackathon (https://medtech.moscow/news/211), the organizers set a goal in 48 hours to develop a model that predicts the toxicity of chemical compounds using ML and DL models.
Our model predicts the most commonly used toxicological characterization, the semi-lethal dose (LD50), given the route of administration of the drug (i.p., i.v., orally, and s.c.), as well as hepatotoxicity. 11 datasets (Datasets folder) with about 35,000 unique molecules were independently collected from open sources, cleaned and processed, descriptors describing the structure of each molecule were extracted from them. The values obtained from the databases had units of mg/kg. To bring them to a convenient form, we converted them to mol/kg and took the inverse decimal logarithm from them.
They tested classification and regression models of machine learning, as well as measured quality metrics. Everything was designed into a single pipeline (Main_Pipeline). The tests were conducted by Syntelly on a closed test set, focusing on their benchmarks. My role in the team was to build the work of the team (I was the captain), find the optimal machine learning model, I also found and processed some of the original datasets on my own, bringing them to a working state, as well as helping to write the final pipeline. As a result, we entered the final, in the top 27 teams (7%) at the end of the competition (there were 80 teams in total, 379 participants)



Murawiecki Daniel, Moscow Institute of Physics and Technology,
May 2023
