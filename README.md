# lambda-twbot-connpass

Based on
- [twbot](https://github.com/gkzz/twbot)

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
├── 38
├── LICENSE
├── node_modules
├── package.json
├── package-lock.json
├── README.md
└── src

3 directories, 4 files
```
