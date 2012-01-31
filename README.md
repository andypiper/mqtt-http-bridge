mqtt-http-bridge.rb
===================

This simple web application provides a bridge between HTTP and [MQTT] using 
a [REST]ish interface. It is possible to GET, POST and DELETE retained messages on a
remote MQTT server.

Examples using curl
-------------------

To get a retained value for a topic:

    curl http://test-mosquitto.heroku.com/test

To publish to a topic:

    curl -X POST --data-binary "Hello World" http://test-mosquitto.heroku.com/test

To delete the retained value for a topic:

    curl -X DELETE http://test-mosquitto.heroku.com/test


[MQTT]:    http://mqtt.org/
[REST]:    http://en.wikipedia.org/wiki/Representational_state_transfer
