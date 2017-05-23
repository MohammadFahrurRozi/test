# qoap-monitoring

qoap-monitoring. 

## Getting Started

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed pellentesque pretium mauris vitae pharetra. Donec sapien augue, viverra finibus arcu et, placerat vestibulum risus.

### Prerequisites

```
# install nodejs
  $ curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash –
  $ sudo apt-get install -y nodejs
  
# install pm2
  $ sudo npm install -g pm2
  
# install redis
  $ wget http://download.redis.io/releases/redis-stable.tar.gz
  $ tar xzf redis-stable.tar.gz
  $ cd redis-stable
  $ make
  $ make test
  $ sudo make install
  
# install mongo
```

### Installing

```
$ git clone https://github.com/husnulhamidiah/qoap-monitoring.git
$ cd qoap-monitoring
$ npm install
```

### How to run

```
$ pm2 start config.yml
```


### How to access

```
your_ipAddress:8000
```

