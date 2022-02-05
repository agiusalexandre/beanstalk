#Create an Elastic Beanstalk environment

1. Create a repository with the eb init command.
~/node-express$ eb init --platform node.js --region eu-west-1

2. Create an environment running a sample application with the eb create command.
~/node-express$ eb create --sample node-express-env

3. Deploy the changes:
~/node-express$ eb deploy

4. Open
~/node-express$ eb open

5. Clean Up
~/node-express$ eb terminate