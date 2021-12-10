# ML-Summative
Deploying emotion model to predict people's emotions based on their tweets
Model was built on a dataset that had six emotions: ANGER, FEAR, HAPPY, LOVE, SADNESS and SURPRISED
The system handles errors by first checking if the user has actually entered something and not an empty space, if user enters a text that is less than or equal to 2 the system tells them that they have entered an invalid tweet hence they have to do it again. One major reason why the app is slow is because once the user clicks to predict, the tweet entered is first of all cleaned and then converted to a format that is acceptable for our model before predictions are made

Link to presentation: https://www.loom.com/share/cddbb93e03374e75b88248cd74972eb2
Second link that highlights some error handling issues: https://www.loom.com/share/a77219f1b66042d9a3102a5ca57d1068
