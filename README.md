# Centre-loss
Centre loss is a loss function proposed in the paper "Wen et al. A Discriminative Feature Learning Approach for Deep Face Recognition. ECCV 2016". It can better discriminate the samples regarding their classes. This is achieved by introducing centres of the deep features in each class and penalise the errors between the features and their class centres.

Using this centre-loss module, you need to:
Implement on Tensorflow platform\
Instaniate the centre-loss class with number of classes and number of features\
Call the instaniated module like a normal keras layer


![image](https://user-images.githubusercontent.com/80739689/119055037-b432a280-ba1c-11eb-8bbb-ab17164f2c48.png)
