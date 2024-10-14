<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multilayer Perceptron Model with Three-Character Context</title>
</head>
<body>
    <h1>Multilayer Perceptron Model with Three-Character Context</h1>
    <p>
        This repository contains a modified version of the traditional bigram language model, implemented as a 
        multilayer perceptron (MLP). Unlike standard bigram models that rely solely on the previous character 
        to predict the next one, this model utilizes the context of the last three characters, 
        allowing it to capture more complex patterns in the sequence.
    </p>
    <p>
        The implementation is inspired by Andrew Kaparthy's work, but with significant modifications 
        that enable it to achieve a lower loss than his original model. The use of an MLP and a broader 
        context window allows for improved predictive accuracy, making this model a more robust solution for 
        sequence-based tasks.
    </p>
    <p>
        Explore the notebook to dive into the architecture and see how these enhancements contribute 
        to the model’s performance.
    </p>
</body>
</html>
