# Handwritten_Digit_Recognition_SVM 
____________________________________

Handwritten digit recognition is the process to provide the ability to machines to recognize human handwritten digits. It is not an easy task for the machine because handwritten digits are not perfect, vary from person-to-person, and can be made with many different flavors.

Procedure :                                                                                                                    
        => Analyse the problem that is need to be found.                                                                         
        => Collect dataset using Scikit-learn Digit Dataset that has 10 classes with total number of samples as 1797. Single image of dimension 64 as 8 x 8 matrices.                                                    
        => Load dataset and summarize detials such as number of rows and columns.                                                                    
        => Using iloc segregate the independant and dependant values. (iloc - helps to select values belonging to particular row and column)         
        => Split train and test set for validation.                                                                                               
        => We do feature scaling to scale our data to make all features contribute equally to result.                                          
        => Use Logistic regression algorithm.                                                                                          
        => Training model for preprocessing dataset.                                                                            
        => Confusion matix used for validation that gives accuracy with true postive, true negative, false positive, false negative values.                
        => Observe how our model classify our new data.     
