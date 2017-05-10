# celery-flower

Container with [flower](http://flower.readthedocs.org/en/latest/) based on ubuntu 14.04.

The container is configured to use flower persistence.

Default broker used is Redis.

To start the container execute the following commands (docker >= 1.9):

```
docker run --net=host -v /var/flower:/var/flower/db -d bmwant/celery-flower
```

You can find an example config [here](https://github.com/bmwant/celery-flower/blob/master/flowerconfig.py)

