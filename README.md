# CS6910-assignment_2
CNN model

the wandb link of part A is https://wandb.ai/theindianwriter/cs6910-assignment2-part_a/reports/Assignment-2-Part-A--Vmlldzo2MTQxMjg
the wandb link of part B is https://wandb.ai/cs20m038/DL_Assign_2B/reports/Assignment-2-Part-B--Vmlldzo2MTM5MTY
the wandb link of part C is https://wandb.ai/theindianwriter/cs6910-assignment2-part_a/reports/Assignment-2-Part-C--Vmlldzo2MTQ4NDc

There are 3 colab notebook each having different parts of the assignmnent i.e part a,part b, part c.

For part A: First of all you need to download the iNatural Dataset and save it in your drive at appropriate location to use all the notebooks.
Then check the respective notebooks.
For part B : To check on any test dataset simply open the notebook ***DL_Assign_2_PartB*** and go to the ***Initializing the model parameters*** section and put the directory address for test data under ***test_data_directory = 'test data drectory address'***
then go to ***uncomment below part and comment wandb logs in testModel and trainModel function to run without wandb*** section andprovide appropriate parameters to the ***startTraining*** function for eg. ***startTraining(model_name ="densenet161", num_classess =10, batch_size =32, num_epochs=2,feature_extract=False,no_layers_to_unfreeze=1,lr=0.001,gamma=0.1,opt = "sgd")***
Note : You can choose the following model name : 
***["inceptionv3","resnet18","resnet34",resnet50", "resnet101","vgg11","vgg19" "squeezenet", "densenet121","densenet161"]***

Similarly ***"DL_Assign_2_PartB_withWandB.ipynb"*** notebook is for sweep in partB
***"DL_Assign_2_PartB_Q3_Feature_Extract_Comparison.ipynb" and "DL_Assign_2_PartB_Q3_preTrainedComparison.ipynb"*** is for plottig graphs in partB Q3



