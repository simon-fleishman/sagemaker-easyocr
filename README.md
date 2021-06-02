# sagemaker-easyocr

  Based on tutorial htpps://aws.amazon.com/getting-started/hands-on/build-train-deploy--machine-learning-model-sagemaker/#

  The code is mostly copied from hithub.com/hunkim/sagemaker-aihub/tree/master/easy_ocr 

(0) You must have an AWS account. If you do not already have an account, choose Sign up for AWS and create a new account. Log in to your account 

(1) Create an Amazon SageMaker notebook instance 

   a. Sign in to the Amazon SageMaker console, and in the top right corner, select your preferred AWS Region 

   b. In the left navigation pane, choose Notebook instances, then choose Create notebook instance 

   c. On the Create notebook instance page, in the Notebook instance setting box, fill the following fields: 

      For Notebook instance name, type say SageMaker-easyocr 

      For Notebook instance type, choose ml.t2.medium. 

      For Elastic inference, keep the default selection of none. 

   d. In the Permissions and encryption section, for IAM role, choose Create a new role, and in the Create an IAM role dialog box, select Any S3 bucket and choose Create role. 

       Note: If you already have a bucket that you’d like to use instead, choose Specific S3 buckets and specify the bucket name. 
       Amazon SageMaker creates the AmazonSageMaker-ExecutionRole-*** role 
   e. In Git section add repository https://github.com/simon-fleishman/sagemaker-easyocr.git 

   f. Keep the default settings for the remaining options and choose Create notebook instance. 

      in the Notebook instances section, the new SageMaker-easyocr notebook instance is displayed with a Status of Pending. The notebook is ready when the Status changes to InService. 

(2) Execute the cells one-by-one

(3) Stop and delete the notebook
       
