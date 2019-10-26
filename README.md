### To start workshop, create an Amazon SageMaker Notebook Instance

An Amazon SageMaker notebook instance is a fully managed machine learning (ML) Amazon Elastic Compute Cloud (Amazon EC2) compute instance that runs the Jupyter Notebook App. You use the notebook instance to create and manage Jupyter notebooks that you can use to prepare and process data and to train and deploy machine learning models. 


**To create an Amazon SageMaker notebook instance**

1.  Open the Amazon SageMaker console at [https://console.aws.amazon.com/sagemaker/](https://console.aws.amazon.com/sagemaker/).
    
2.  Choose **Notebook instances**, then choose **Create notebook instance**.
    
3.  On the **Create notebook instance** page, provide the following information (if a field is not mentioned below, leave it default):
    
    1.  For **Notebook instance name**, type a name for your notebook instance.
        
    2.  For **Instance type**, choose `ml.m5.xlarge`. This is the least expensive instance type that notebook instances support, and it suffices for this exercise.
        
    3.  For **IAM role**, choose **Create a new role**, then choose **Create role**. In 'create IAM Role' pop up window, select 'Any S3 bucket'. 
        
    4. For Git repositories, select 'clone public git repo ***' and provide folowing repository: ``https://github.com/rthamman/tensor-world-2019.git``
        
    5.  Choose **Create notebook instance**. In a few minutes, Amazon SageMaker launches an ML compute instance—in this case, a notebook instance—and attaches an ML storage volume to it. The notebook instance has a preconfigured Jupyter notebook server and a set of Anaconda libraries. 

    6. In few minutes Amazon SageMaker Instance will be in running state, Click **Open Jupyter** to continue. This action will open Jupyter Notebook in your browser window. 

    7. In the Jupyter Notebook console, in the Files tab, you should see following
    
     		 sentiment-analysis.ipynb
     		 tf-boston-housing.ipynb
     		 tf-distributed-training.ipynb
   
    8. Choose the Ipython notebook and follow the instructions in Jupyter Notebook. 