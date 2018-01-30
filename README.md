# AzurePythonWebApp
Setup tutorial for a basic Azure Web App using Python and the Flask API

Steps:

GET AZURE ACCESS
1. Create Dreamspark account on Microsoft Imagine Website
2. Verify student status to gain azure access
3. Login to azure portal, press new, create web app
4. Select created web app on dashboard
5. Select Deployment options -> Choose Source -> Local Git Repository
6. If required, create user by entering username and password
7. Select OK to finish deployment setup
8. Select Properties on the left panel and scroll to the GIT URL. Copy the url.

CREATE LOCAL REPOSITORY
1. Run in Terminal 
    1. git clone https://github.com/Azure-Samples/python-docs-hello-world.git
    2. git remote add azure <paste azure git url>
    3. git push azure master 
        1. Enter web app user password
2. Return to Azure Overview tab and press browse to view the deployed site
3. Change ‘main.py’ in your local repo to return ‘Hello Azure!’
4. Commit and push changes
5. See your modified application!


Code Used From: 

https://github.com/Azure-Samples/python-docs-hello-world.git 

https://docs.microsoft.com/en-us/azure/app-service/app-service-web-get-started-python
