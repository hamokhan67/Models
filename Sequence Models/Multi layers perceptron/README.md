<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modified Bigram Model</title>
</head>
<body>
    <h1>Modified Bigram Model with Context of Three Characters</h1>
    <p>
        This repository contains a modified version of the traditional bigram language model. 
        While bigram models usually rely on just the previous character to predict the next one, 
        this model expands on that idea by using a context of three characters. 
        By taking into account the last three characters, this model can capture more context 
        and dependencies in the sequence, leading to improved performance over simple bigram models.
    </p>
    <p>
        The code is heavily inspired by Andrew Kaparthy's work, but with modifications that enable 
        the model to achieve a lower loss than the original version. This adjustment demonstrates 
        how incorporating a larger context window can significantly improve the predictive capabilities 
        of the model.
    </p>
    <p>
        Feel free to explore the notebook to understand the modifications and performance improvements, 
        and to use it as a base for further experimentation.
    </p>
</body>
</html>
