configure serverless - 
serverless config credentials --provider aws --key  ABC --secret XYZ --profile serverless-admin

create serverless app -
serverless create --template aws-java-maven --path my-serverless-app

create jar 
mvn clean install

serverless deploy



