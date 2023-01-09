# Salary_esttimation_using_KNN
_________________________________

Predicting whether the job applicant got salary above 50k or not from previous company. - HR

Procedure :                                                                                                                    
        => Analyse the problem that is need to be found.                                                                         
        => Collect dataset with input as age ,eduation_num, capital gain and Hours per week .                                               
        => Load dataset and summarize detials such as number of rows and columns. (Pandas).
        => Map data from text to binary. If data is <=50k mapped as 0 and >=50 as 1.
        => Using iloc segregate the independant and dependant values. (iloc - helps to select values belonging to particular row and column)         
        => Split train and test set for validation.                                                                                               
        => We do feature scaling to scale our data to make all features contribute equally to result.                                          
        => Use K-Nearest Neighbour algorithm. Based on minkowski disatnce metric classify the data points.
        => Find best K value based on low mean error.
        => Training model for preprocessing dataset.                                                                            
        => Confusion matix used for validation that gives accuracy with true postive, true negative, false positive, false negative values.                
        => Observe how our model classify our new data.     

Evaluating models performance by confusion matix and cross validation with visual representation is also carried out in the code 

