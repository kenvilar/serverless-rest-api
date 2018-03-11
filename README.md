# serverless-rest-api
Core Service for a Notes REST API

* Install serverless globally (`npm install serverless -g`)
* 

#####Commands
* `serverless config credentials --provider aws --key accesskey --secret secretaccesskey`       (change the 'accesskey' and 'secretaccesskey' with your existing key credentials)
* `serverless create --template aws-nodejs --path kenService`   (create a boilerplate for a service)
* `cd <name-of-service>`    (get inside to the service folder)
* `sls deploy -v`   (deploy verbose)
* (Once the deploy is finished, copy the endpoint url and then open it in browser)
* `sls deploy function --function hello`    (specify to only deploy the function you've changed, in which case here is the hello function)