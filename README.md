# Monk-AI-Programming Test
This repository  is based on three data sets which are classified and
analyzed with different activation functions: 

datasets ( iris, mnist , bank-notes)

## Common Setup for the Datasets :

Since Few steps are common for the initial stage of this algorithm ill explain
the common step below:

1 – To upload any dataset we can use Pandas library :
Eg – dataset = pd.read_csv( url , or direct data set name )

2 – To select the paramentrs for k0 , k1 by dividing the data set with respect
to its contains
in my code i have paramentrs k0 ,k1 as x , y

3 – Since we have words or string in our data set we need to convert them into
arrays or number to classify it
i have used Labled encoder function to transform the parametres

4 – To classify any model we need to splite the data set into tranning , testing .
In my code i have used from sklearn , train test-split model with test
size as 20 % on any ramdom simple
