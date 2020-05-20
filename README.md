# lambda-twbot-connpass

Based on
- [lambda_twbot](https://github.com/gkzz/lambda_twbot)

## TL;DR

```
$ git clone https://github.com/gkzz/event-news-bot.git \
&& cd event-news-bot
$ aws configure
$ npm init
$ sudo npm install -g serverless
$ serverless create \
> --template aws-python3 \
> --name src \
> --path src
$ sudo npm install --save serverless-python-requirements
$ sudo npm install --save serverless-dotenv-plugin
$ sudo npm install --save serverless-offline
$ cat src/handler.py.tmpl > src/handler.py
$ cat config/.env.tmpl > config/.env
$ serverless deploy
```

``` 
$ tree -L 1
.
├── LICENSE
├── node_modules
├── package.json
├── package-lock.json
├── README.md
└── src

2 directories, 4 files
```
