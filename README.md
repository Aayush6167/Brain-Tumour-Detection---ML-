# Cancer-Detection-using-ML
![image](https://user-images.githubusercontent.com/77532204/232719794-9b1359a7-95db-43d4-826a-c8d8d778902c.png)

This is an python based ML project which predicts the presence of Brain tumour in human brains.
In this project we have used 1. numpy
                             2. pandas
                             3. matplotlib
                             4. sklearn
                             
# We could have also used standard scaler and min max scaler
# But we used Feature scaler because the RGB value of an image ranges from 0-255
# So we devided the samples by 255
# That is why we are getting all outcomes in 0 or 1

# Principle Component Analisys (Data reduction algo.)
# reduce number of atributes without significant loss in info.

# Training Model
# high C means "Trust this training data a lot", while a low value says 
#"This data may not be fully representative of the real world data, so if it's telling 
#you to make a parameter really large, don't listen to it"

                                                                Training Score: 0.9938587512794268
                                                                Testing Score: 0.963265306122449
