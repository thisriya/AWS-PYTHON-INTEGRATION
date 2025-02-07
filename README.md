STEPS: 
1.) Create a AWS Services account using debit card, email, phone number. 
2.) Go to Amazon Bedrock. 
3.) Click on select model. 
4.) Select LLama 3 8B instruct from Meta. 
5.) Click available to request, further request access and then submit after keeping 
everything default. 
6.) Now we can use the chat/text using the model selected. Type the prompt. In my 
case I entered ‘Best places to visit in banaras’. 
7.) You will get the result. 
Now we will implement it by integrating LLama and AWS together. 
1.) Create a ‘requirements.txt’ file that has all the packages to install so that we can 
install them all together. boto3 is used for integrating python and AWS together. 
awscli is command-line interface that manages AWS services. 
2.) Now install anaconda and set the bin path in environment variables. 
3.) Now create a virtual environment using command ‘create -p myenv 
python=3.12 -y’. 
4.) Then activate the myenv by command ‘conda activate myenv’. 
5.) Now write the code. In the code we need model-id and region. Make sure to 
select the correct region so that the model is accessible there. 
6.) For knowing the model id, apply the model id then click to info there we have 
model id. And for region we need to check to top right just to left side of our 
profile. 
7.) Now we need to configure the AWS by command ‘aws configure’. We need 
Access key Id and  Secret Access Key. 
8.) For creating these credentials go to your account , click on secret credentials, 
click on create access key, now access key for the user is created. 
9.) After configuration we need to enter the Access key Id and  Secret Access Key, 
region and type of data that is ‘json’ everytime. 
10.) Now run the code , you will get the same output as when you were getting on 
using the AWS services model. 
