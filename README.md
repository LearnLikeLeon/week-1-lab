# week-1-lab
Creating an AWS Account and interacting with AWS CloudShell

The image of the final project is shown below:

![week_1_lab](https://user-images.githubusercontent.com/121564302/232353260-371df67e-51a9-4d24-9177-ff5306399185.png)


Create development environment that is cloud-based such as : AWS CloudShell

## Let's create the project scaffold :

  * Create a GitHub Account and Log In to the created GitHub Account where your projects will be published (This will be your Portfolio).

  * Create a new GitHub repository which will be used for this project with a 'README' file and a '.gitignore' file with a Python gitignore template.
  
  * Edit the 'ReadMe' file to document achieved milestones.

  * Create a new AWS Account or Log In to your created AWS Management Console.
  
      - We will be using Amazon Web Services through this project and launch your AWS CloudShell environment known as  a browser-based Linux Terminal.
      
  * Create development environment that is cloud-based such as : 
  
      ### AWS CloudShell
        
        - To see the list of tools available in your AWS Account by Default;  type the following command :
        
          $ ls /usr/local/bin -la 
          
        
        RQ : You will see the AWS Command Line Interface " AWS CLI V2 " 

           -> There is the Elastic Beanstalk Command Line Interface " eb "
           -> There is the Elastic Container Command Line Interface " ecs-cli "
           -> There is Flask 
           -> There is the Serverless Application Manager " sam "

          NB: If the tool you need is not part of the default list, you can even install your own.
          
          
  * Let's install the AWS Cloud Development kit " AWS CDK " from your AWS CloudShell :
  
      - Let's work with AWS CDK in Python or you can chooose your development language:
      
          $ sudo npm install -g aws-cdk

      - Let's create a directory called " AWS_CloudShell_Project_1 " :

          $ mkdir AWS_CloudShell_Project_1

          $ cd AWS_CloudShell_Project_1

      - Let's create a AWS CDK Application by invoking " cdk init " in the created empty directory :

          $ cdk init --language python

       - Let's view all the generated files related to this AWS CDK Python Project :

          $ ls


NB: Congratulations, you've created an AWS Python CDK project using AWS CDK command in your AWS CloudShell Environment.

  * To delete your AWS CloudShell home directory, hit " Actions " and select  " Delete AWS CloudShell home directory "
