# Handwritten_Digit_Recognition_SVM 
____________________________________

Handwritten digit recognition is the process to provide the ability to machines to recognize human handwritten digits. It is not an easy task for the machine because handwritten digits are not perfect, vary from person-to-person, and can be made with many different flavors.

Procedure :                                                                                                                    
        => Analyse the problem that is need to be found.                                                                         
        => Collect dataset using Scikit-learn Digit Dataset that has 10 classes with total number of samples as 1797. Single image of dimension 64 as 8 x 8 matrices. Our dataset is not an image but values of image. We define them as pixel values.                                                    
        => Load dataset and summarize detials such as Data = (1797, 64), Image = (1797, 8, 8), Target = [0 1 2....8 9].                                           
        => Visualise Data , it is array format containing values from 0-16 in 8x8 matrix with a diension of 64.
        => Segregate Dataset into x and y, where x = input pixels -> dataset.images.reshape(imagedataLength, -1) where -1 is excluding final array/part and y = output class -> dataset.target where target is output.
        => Split train and test set for validation.                                                                                               
        => Use Support Vector Machine with the types of kernel -> linear Kernel, RBF Kernel, Polynomial Kernel. 
        => Change the tunning parameters C , Degree(only for polynomial kernel), Gamma to determine good accuracy. Choose good C and gamma. 
        => Train the model.                                                                            
        =>  Evaluation and Validation.                
        => Observe how our model classify our new data.     
