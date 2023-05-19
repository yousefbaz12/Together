## PLANT CLASSIFICATION
What is required now is to start with the first planting guide feature for the awareness app, which is to identify the plant's type ! 

We have 3 Models to build based on the 3 provided datasets : 

If this plant has leaves.. we can know it from the shape, texure & margins of the leaf.

If this plant is still small, can we know from the shape of this small seedlings its type?

If this plant is a Flowering plant, we would like to know its name and data like the rest of the plant...


Here are the 3 datasets that we will use :

`1.Codes and datasets`

https://www.kaggle.com/competitions/leaf-classification/overview  (Leaves)


https://www.kaggle.com/datasets/alxmamaev/flowers-recognition (Flowers)


https://www.kaggle.com/competitions/plant-seedlings-classification/overview (Seedlings)

## Updates  

1- I have changed the flowers dataset to another one which provide more classes (16 rather than 5 classes) and images for each class and therefore our model is more efficient than before, covering more flower types than the previous dataset.

The new dataset link :  https://www.kaggle.com/datasets/l3llff/flowers 

2- I developed the 2 models for plant identification feature which are `LEAVES` & `FlOWRES` Models, and the third model `SEEDLINGS` will be used as an added feature, it will be used to identify if the seedlings is a plant or a weed ?
