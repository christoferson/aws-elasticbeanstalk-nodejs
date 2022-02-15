# aws-elasticbeanstalk-nodejs
Aws Elastic Beanstalk NodeJS

### Local Debug

curl http://127.0.0.1:3000/

curl -X POST http://127.0.0.1:3000/ -H 'Content-Type: application/json' -d '{"login":"me","password":"password"}'

curl -X POST http://xxxx.eu-west-1.elasticbeanstalk.com/  -d '{"login":"me","password":"password"}'

curl -X POST http://xxxx.eu-west-1.elasticbeanstalk.com/scheduled  -d '{"login":"me","password":"password"}' -H "x-aws-sqsd-taskname: mytask" -H "x-aws-sqsd-scheduled-at: nextweek"
