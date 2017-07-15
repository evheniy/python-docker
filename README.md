# Python 3 anaconda pack with running jupiter notebook

## How to install

* Install [docker](https://docs.docker.com/engine/installation/)
* Install [node](https://nodejs.org/)
* Clone repository:

```bash
$ git clone https://github.com/evheniy/python-docker.git
$ cd python-docker
```

## How to use

### Build

Build docker image

    $ npm run build
    
Remove image

    $ npm run rm
    
To see list of images

    $ npm run list
    
### Run

Run container

    $ npm start
    
And open [http://localhost:8888](http://localhost:8888/) with password **root**.

Stop container

    $ npm stop
    
To see running containers

    $ npm run active
    
You should not use node if you can check scripts in package.json and run it manually.