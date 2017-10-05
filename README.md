# got-ml

###An Experiment with Data Science and Machine Learning###

Since we have two years to go for the next season to air, I took this opportunity to predict the possible character deaths in season 8 of the show using Machine Learning

I have run Five-Fold cross validaiton 100 times and achieved an accuracy of 90%

###Creating the Model###

For the model I took in consideration a character's name, occurance in all the books, marital status, age, sex, popularity, house, culture , etc

On that I ran an SVM to classify the data followed by Five fold cross validaiton, a hundred times. According to the model the top 5 deaths in Season 8 could be:

Character            | Possibility
-------------------  | -------------
Danaerys Targereyan  | 91.374%
Theon Greyjoy        | 90.203%
Gregor Clegane       | 90.179%
Melisandre           | 90.152%
Lord Varys           | 90.076%


