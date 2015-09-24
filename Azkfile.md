# Lobsters :: Azkfile.js

### How to run

1) Before starts Lobsters for the first time you should run this command:

```sh
# initial lobsters setup
azk shell lobsters -c'bundle exec rake db:setup RACK_ENV=production'

# sphinx
azk shell lobsters -c'bundle exec rake ts:rebuild RACK_ENV=production'
azk shell sphinx -c'./entrypoint.sh sphinx'

# start all
azk restart -Rvv
```

2) Open http://lobsters.dev.azk.io/ and start with this user:

- user: test
- password: test

--------------------

## azk Quick Start

#### [Install azk](http://docs.azk.io/en/installation/README.html)

```sh
# easy install
curl -Ls http://azk.io/install.sh | bash
```

#### Start azk

```sh
# easy start with --reprovision and --verbose
azk start -Rv
```

#### deploy production to Digital Ocean

We are using this system to deploy: https://github.com/azukiapp/docker-deploy-digitalocean

```sh
azk shell deploy
```

--------------------

### Other azk commands

#### systems status

```sh
$ azk status
```

#### detailed systems info

```sh
$ azk info
```

#### stop all containers

```sh
$ azk stop
```

#### restart all container

```sh
$ azk restart
```

#### restart and reprovision

```sh
$ azk restart -Rv
```

#### check logs

```sh
$ azk logs
```

--------------------

### more on azk

- Official Site
  http://azk.io
- Github
  https://github.com/azukiapp/azk
- Documentation
  http://docs.azk.io
- Images directory created by the azk team
  http://images.azk.io

### Contribute to azk

- Star azk on Github
  https://github.com/azukiapp/azk
- Report an issue
  https://github.com/azukiapp/azk/issues/new
- Help solving a reported issue
  https://github.com/azukiapp/azk/issues
- Check out our awesome sponsors
  http://azk.io/#sponsors

### Stay in touch with the azk team

- Sign up the weekly digest
  http://www.azk.io/#newsletter
- Follow the blog
  https://medium.com/azuki-news
- Talk to our support (chat)
  https://gitter.im/azukiapp/azk (English) e https://gitter.im/azukiapp/azk/pt (Português)
- Facebook
  https://www.facebook.com/azukiapp
- Twitter
  http://twitter.com/azukiapp