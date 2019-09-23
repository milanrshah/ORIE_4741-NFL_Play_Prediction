# ORIE_4741-NFL_Play_Prediction
by Milan Shah (mrs282) and Jibran Gilani (jg793)

Research Question: Would it be possible to use machine learning techniques to help NFL defenses combat offenses by predicting the most likely play they will run?

During each NFL game, we only see about 11 minutes of action during the 60 minute runtime. Even then, the action and results are only a fraction of the research and work that gets put in by coordinators and coaches to prepare for matchups. As a defensive coordinator, part of that research is being able to guess what the opposing offense will do for each play and provide the proper scheme and design against that play. This process depends heavily on their ability to correctly predict what the offense has planned.

We plan on using a detailed NFL play-by-play dataset to predict what play type will appear next given certain variables about the game conditions. We will approach this as a binary classification problem at first but may also expand to predict pass length (shallow, medium, deep) or field location (right, middle, left). Even more depth could be added if we include type or run or pass (e.g. pitch or play action) but the initial focus will be on predicting run vs pass. We may also add to the dataset by including data about the opponent that may factor into a coordinators decision. Once a model is built, it can be tested against ongoing games during the 2019 season if there is a team, offensive coordinator and offensive player combination that is similar to the years in the dataset.
