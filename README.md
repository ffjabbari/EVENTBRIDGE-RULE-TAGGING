
FRED J's Complex EventBridge

- `npm install @aws-cdk/core` install all needed packages per your import as follows
**** FRED NEVER EVER EVER INSTALL ANY CDK PACKAGE GLOBALLY ****
388* npm install @aws-cdk/aws-events
  389* npm install @aws-cdk/aws-events-targets
  390* npm install @aws-cdk/aws-lambda
  391* npm install @aws-cdk/aws-iam
  392* npm install @aws-cdk/aws-sqs
  393* cdk2 bootstrap aws://636090713215/us-east-1
  npm install -g typescript   --- IS OKAY TO INSTALL TYPESCRIPT GOLBALLY BUT NEVER ANY CDK..
  SEE FRED CDK Package has many versions and you must manually per project do this command to install them 
  npm install @aws-cdk/core@1.x       OR
  npm install W@aws-cdk/core@2.x       
  OR ANY OTHER ONE YOU NEED.  ALWAYS INSTALL MANUALLY PER PROJECT
  394* npm run build
  396  npm run build
  397  cdk2 synth
  398  cdk2 deploy --verbose
  399  cdk2 bootstrap aws://636090713215/us-east-1
  400  cdk2 synth
  401  cdk2 deploy --verbose
  402  cdk bootstrap aws://636090713215/us-east-1
 
  405  \tnpm run build
  406  aws configure
  407  npm run build
  408  cdk2 bootstrap aws://636090713215/us-east-1

  410  cdk --version
  411  cdk bootstrap aws://636090713215/us-east-1
  412  npm run build
  413  cdk bootstrap aws://636090713215/us-east-1
  414  cdk synth
  415  cdk deploy
cdk destroy

NOW FRED you can to cdk1 deploy --verbose

REMEMBER you can use CDK1 or CDK or CDK2 because you got alias setup in your ~/.zshrc         That is the only reason fred...
  416  pwd

  419  git remote set-url origin git@github.com:ffjabbari/https-github.com-willdady-cdk-eventbridge-no-match-rule.git
  420  git status
  421  git add .
  422  git status
  423  git push -u origin master
  424  git commit -ma"change for this work..."
  425  git push -u origin master
  426  git push origin head


- `npm run build` compile typescript to js
- `npm run watch` watch for changes and compile
- `npm run test` perform the jest unit tests
- `cdk deploy` deploy this stack to your default AWS account/region
- `cdk diff` compare deployed stack with current state
- `cdk synth` emits the synthesized CloudFormation template
