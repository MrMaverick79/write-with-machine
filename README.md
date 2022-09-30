# Welcome to the Write With M(achin)e :computer: :memo:

**Author: Brendan Tuckerman**

**Overview:** This project is an example of a machine learning regression. It uses the ML5  library to suggest lines of poetry in the style of Emily Dickinson.

    This is my letter to the world,
       That never wrote to me, --
    The simple news that Nature told,
       With tender majesty.

    Her message is committed
       To hands I cannot see;
    For love of her, sweet countrymen,
       Judge tenderly of me!


This folder stores the Python Environment, the Models, and the original text which are used to train the models. 

## Steps

- [x] Develop an environment.

    Training a model with the CharNNN library requires access to tensorflow, which requires some pretty simply Python scripting. The instructions for this can from accessed the [github for the CharNNN library](). Be sure to use Python 3.6 as per the instructions 

- [x] Train the model using the 'Complete Poems of Emily Dickinson'

        I used [this](https://www.gutenberg.org/ebooks/12242) version of Emily Dickinson's complete poems and created a new txt file, with everything but the poems cut out.

        

- [] Generate predictions using the model
- [] Creat a front end to allow users to enter text


## Inspiration 

[Selected Stories](https://cvalenzuela.github.io/Selected_Stories/)

[Nabil Hassein's generative DOOM](https://nabilhassein.github.io/generative-DOOM/)


## Resources and tutorials:

[Python virtualenv on ArchLinux](https://wiki.archlinux.org/title/Python/Virtual_environment)

[ML5.js Library](https://learn.ml5js.org/#/)

[Project Gutenberg](https://www.gutenberg.org/)

[Working with Lexical](https://github.com/facebook/lexical)

[CharNNN Library from ML5](https://learn.ml5js.org/#/reference/charrnn)

[Creating a VirtualEnv to run the Python needed to train a model](https://www.youtube.com/watch?v=nnhjvHYRsmM)

[Training a CharNNN using the model in ml5.js](https://github.com/ml5js/training-charRNN)

[Text Generation with LTSM and Spell](https://www.youtube.com/watch?v=xfuVcfwtEyw)