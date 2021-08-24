# Amazon ML challenge 2021 conducted in Hackerearth (111th rank)

## DATASETS

https://www.kaggle.com/nakuuu/amazon-ml-challenge-2021-hackerearth

You can find the cleaned dataset here,

https://www.kaggle.com/rohirama2/cleanamazondata

After running the em_partX.ipynb files (We are technically splitting the dataset and encoding the data and exporting it as npy) we get the following are the npy files

![image](https://user-images.githubusercontent.com/59824729/130634704-d416a767-6194-4ab2-a05e-040de338fb62.png)

They can be found on Kaggle here,

https://www.kaggle.com/rohithramakrishnan/datapart1
https://www.kaggle.com/anirudhvadakedath/datapart2
https://www.kaggle.com/anirudhvadakedath/datapart3
https://www.kaggle.com/rohithramakrishnan/datapart4
https://www.kaggle.com/avrudhv/datapart5 (The code for this hasn't been uploaded, but basically here, similar to other em_part notebooks, we will give the npy file name as 
y_p5.npy and encoding_p5.npy, and also train_vec = train_vec[484668*4:])

Encoded test dataset is here,

https://www.kaggle.com/anirudhvadakedath/test-encoding (Kind of similar to how we did the em_partX.ipynb, but we passed in the full test data and encoded it. And we didn't have the additional work of handling labels here). 

Since the dataset was too large, we dropped quite a bit of datapoints in the training dataset whose labels occured moderately less (around 200 ish)

We trained the respective dataparts one after the other. 
