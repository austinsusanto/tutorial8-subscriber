# Reflection 1

What is _amqp_?

AMQP stands for Advanced Message Queuing Protocol. It is a procedure used by applications to communicate reliably and efficiently.

What it means? guest:guest@localhost:5672 , what is the first guest, and what is
the second guest, and what is localhost:5672 is for?

The first guest refers to the username that will be used for the AMQP and the second guest refers to the password. The localhost:5672 refers to the location where the amqp server is running. In this case, the server is running on the local machine on port 5672.

# RabbitMQ Queued Messages Chart

![Queued Messages Chart](/assets/queued-messages.png)

The total number of queued message in the chart is 30 because I've run the publisher program for 6 or more times. Everytime the program has been run, 5 messages are sent. So when the program is run 6 times or more, there are about 30 messages to be queued.
