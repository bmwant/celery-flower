# celery-flower

Container with [flower](http://flower.readthedocs.org/en/latest/) based on ubuntu

The container is configured to use flower persistence.

To start the container execute the following commands (docker >= 1.9):

docker run --name some-flower -v /var/docker_conf/flower:/etc/flower -v /var/docker_data/flower:/var/flower/db -d njordr/celery-flower

You can find an example config in my [git repo](https://github.com/njordr/celery-flower)

