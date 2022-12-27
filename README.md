# Feedback_form
Website to take customer feedback

Automate static website deployment from Github to S3 using AWS CodePipeline

Description - Automatically deploy changes made to the GitHub repository of the static website to AWS S3. The change you make will be instantly available on live website www.postfeedback.com.

You don’t need to clone the git repository to make changes. You can do it from the github.com website itself. After configuring the pipeline, you don’t need to login to AWS. Everything happens automatically under the hood. 

AWS services used 
S3 Bucket - To store the html pages of the website for static website hosting 
CodePipeline - To automate the process, user updates the html pages in Github and it is taken care by the Codepipeline to update it diecetly in 

Github - To store the website 
