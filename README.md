# LambdaS3Project
Initial LambdaS3 Project learning curve

This project is an attempt to use the CreateThumbnail.py Lambda python example in the cloud.  

PREREQUISITES
<BR>
1) AWS account.<BR>
   Recommend that you spend some time to setup TWO FACTOR authentication on your ROOT AWS account *AND*
   establish a ADMIN login for Lambda using TWO FACTOR authentication.  For example "LambdaAdmin" and "LambdaUser" .<BR>
   http://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html<BR>
   Some of the information will be at the above link
<BR>
2) Install the AMAZON AWS CLI (Command Line interface) (used by the lambda installer)<BR>
   https://aws.amazon.com/cli/
<BR>
3) Create an Amazon S3 bucket for input and output lambda activity.   
<BR>
4) WINDOWS7 SYSTEM WITH PYTHON 2.7 installed<BR>
   Go to this link to download python 2.7
   (At this time Amazon Lambda seems to require Python 2.7)
   https://www.python.org/downloads/
<BR>
5) Download the rackspace lambda installer (I used the pip install command which worked for me)<BR>
   http://blog.rackspace.com/introducing-the-lambda-uploader-for-python/
   https://github.com/rackerlabs/lambda-uploader
  <BR>
  With all these steps done, the goal is that you can download this GITHUB project and test the lambda service.
  The configuration script in this repository uses my AWS credentials, which will not work for your case.  You will need to replace this with the aws string of your ADMIN account found by going to the IAW page for your admin account and cut/pasting the string into your lambda.json file.
