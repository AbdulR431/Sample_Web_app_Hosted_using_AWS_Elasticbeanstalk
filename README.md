# Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk
Mini Project: Sample web application hosted using AWS Elastic Beanstalk.

First step in application creation using elastic Beanstalk

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%202.PNG)

Then we need to create an environment

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%203.PNG)

next choose webserver environment

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%204-2.PNG)

choose the platform u need

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%204-3.PNG)

if you want then you can use custom code or else we can go for sample one

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%204-4.PNG)

select the role or create one

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%204-4.PNG)

choose the key

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%205.PNG)

we dont need any vpc for this sample application so select -

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%206-1.PNG)

select the availability zones you want to deploy your instances, let all other options be default

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%206-2.PNG)

select databases if needed

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%206-3.PNG)

choose the default volume type

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%207-1.PNG)

choose the security group and cloud watch monitoring interval

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%207-2.PNG)

select health reporting whether enhanced or basic to save costs I have selected basic one

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%208-1.PNG)

leave manged platform updates as we are not updating the application, but if needed then configure it, also enter an mail to get inportant info regarding your environment

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%208-2.PNG)

review everything

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%209.PNG)

then click confirm to create the environment

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%2010.PNG)

you can use the link under the domain to check whether your web application is hosted or not.

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%2011.PNG)

if you go to the ec2 console you can see that an instance is launched by beanstalk for us

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%2013.PNG)

In the monitoring section you can see the cpu utilization, networking and other metrics

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Step%2014.PNG)

if you open the link provided under domain you can access your web application

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/Final.PNG)

finally select the application and go to actions then delete the application to avoid further costs

![](https://github.com/AbdulR431/Sample_Web_app_Hosted_using_AWS_Elasticbeanstalk/blob/main/Images/deleting%20the%20app.PNG)

# Thank You
# The End
