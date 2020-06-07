# SMOMI3

На первом этапе лабораторной работы необходимо было обучить самостоятельно написанную сеть VGG16.
Как можно заметить на графиках, сеть обучается плохо вне зависимости от параметров.

### BATCH_SIZE = 8   lr = 0.00000004

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/A_train_1.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/A_val_1.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/L_train_1.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/L_val_1.PNG)

### BATCH_SIZE = 8   lr = 0.000007

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/A_train_2.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/A_val_2.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/L_train_2.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/L_val_2.PNG)

 ### BATCH_SIZE = 8  lr = 0.000007 

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/A_train_3.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/A_val_3.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/L_train_3.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/1%D1%8D%D1%82%D0%B0%D0%BF/L_val_3.PNG)

На втором этапе мы использована предобученную на imagenet сеть VGG16. В сети были заморожены сверточные слои и проводилось обучение классификатора.

### BATCH_SIZE = 8   lr = 0.0007

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/A_train_3.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/A_val_3.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/L_train_3.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/L_val_3.PNG)

### BATCH_SIZE = 8   lr = 0.00000011

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/A_train_1.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/A_val_1.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/L_train_1.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/L_val_1.PNG)


### BATCH_SIZE = 8   lr = 0.000001

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/A_train_4.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/A_val_4.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/L_train_4.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/2%D1%8D%D1%82%D0%B0%D0%BF/L_val_4.PNG)


На третьем этапе мы обучали сеть уже с размороженными свёрточными слоями и использовали весовые коэффициенты из предыдущей попытки.

### BATCH_SIZE = 8   lr = lr=0.0000000011

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/A_train_3.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/A_val_3.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/L_train_3.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/L_val_3.PNG)

### BATCH_SIZE = 8   lr = 0.00000000001
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/A_train_1.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/A_val_1.PNG)
![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/L_train_1.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/L_val_1.PNG)

### BATCH_SIZE = 8   lr = 0.000000000001

![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/A_train_2.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/A_val_2.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/L_train_2.PNG)![.](https://github.com/VictoriaIL/SMOMI3/blob/master/3%D1%8D%D1%82%D0%B0%D0%BF/L_val_2.PNG)





