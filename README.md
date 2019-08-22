# Transformers-From-Scratch--Tensorflow
In this Repository , I will upload all my attempts in writing Transformers for different Seq2Seq Tasks. which is really important for Bert
Model
Dataset Link :- https://www.kaggle.com/sunnysai12345/news-summary
>1st Attempt -> Machine Translation (generic Model)

>2nd -3rd Attempt > Based on Text Summarization 

>4th Attempt -> Implemented Masked Loss to remove loss because of padded tokens in decoder prediction

#Idea for Improving model 
>Since pad tokens in Encoder doesnt contain any information so we can also use masking inside decoder to Self  Attention values which can  >help Transformer to learn more effectively

> Transformer is continously decreasing loss so further improvement can be done by training same model for more number of epochs

> Can be Improved by adding more layers and more heads inside Encoder aswell as Decoder
