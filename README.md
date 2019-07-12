# Source code
#Test 
Jenkins Server:
http://3.82.171.238:8080


Visit below url to test the piepline
http://3.82.171.238:8080/job/django/job/testproject/

Build the job and check status.

If the build is successful visit http://3.82.171.238:8000 and check you are getting the Homepage

Follw below steps to test the pipeline is working and if the tast case fails it will send the email notificatoin and code will not be pushed to server.

Clone the https://github.com/brijeshakbari/django-testing-tutorial.git to your github account

Change the content of https://github.com/brijeshakbari/django-testing-tutorial/blob/master/templates/home.html 

Then push the changes to your github account.

Edit the jenkins job 

Replace the existing repo url to your repo url

Add your email address in post build actions.

Build job again and test it.

It should fail and send you an email notification.

Revert the changes of https://github.com/brijeshakbari/django-testing-tutorial/blob/master/templates/home.html 

Push the changes to your repo.

Jenkins job will auto trigger as the changes are pushed to repo

Visit the http://3.82.171.238:8000 and check if you are getting original content.



