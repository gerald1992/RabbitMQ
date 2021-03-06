<<<<<<< HEAD
# PHP code for RabbitMQ tutorials

Here you can find PHP code examples from [RabbitMQ
tutorials](http://www.rabbitmq.com/getstarted.html).

To successfully use the examples you will need a running RabbitMQ server.

## Requirements

### PHP 5.3+

You need `PHP 5.3` and `php-amqplib`. To get these
dependencies on Ubuntu type:

    sudo apt-get install git-core php5-cli


### Composer

Then [install Composer](https://getcomposer.org/download/) per instructions on their site.


### Client Library

Then you can install `php-amqplib` using [Composer](http://getcomposer.org).

To do that install Composer and add it to your path, then run the following command
inside this project folder:

    composer.phar install

## Code

[Tutorial one: "Hello World!"](http://www.rabbitmq.com/tutorials/tutorial-one-php.html):

    php send.php
    php receive.php


[Tutorial two: Work Queues](http://www.rabbitmq.com/tutorials/tutorial-two-php.html):

    php new_task.php "A very hard task which takes two seconds.."
    php worker.php


[Tutorial three: Publish/Subscribe](http://www.rabbitmq.com/tutorials/tutorial-three-php.html)

    php receive_logs.php
    php emit_log.php "info: This is the log message"

[Tutorial four: Routing](http://www.rabbitmq.com/tutorials/tutorial-four-php.html):

    php receive_logs_direct.php info
    php emit_log_direct.php info "The message"


[Tutorial five: Topics](http://www.rabbitmq.com/tutorials/tutorial-five-php.html):

    php receive_logs_topic.php "*.rabbit"
    php emit_log_topic.php red.rabbit Hello

[Tutorial six: RPC](http://www.rabbitmq.com/tutorials/tutorial-six-php.html):

    php rpc_server.php
    php rpc_client.php
=======
# RabbitMQ
>>>>>>> a5c30da2dff3f00d44df4d50c8697e99b07e6777
