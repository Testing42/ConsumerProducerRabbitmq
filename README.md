For this to work you will need to install rabbitmq.

the default way to login if you setup rabbitmq you'll go to the url below

http://localhost:15672/

the default password is username: guest, password: guest

All the project above does is send a message to rabbitmq and the other part of the project consumes the message from the queue.
