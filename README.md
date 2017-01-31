# docker_elasticSearch_logstash
This project is the implementation of elastic search with the logstash using dockers. 
For logstash the already created image on the dockerhub has been used where as elastic search is custom built.

The ip address in the jdbc_connection_string which is in the logstash.conf file is actually the hostip address. Inorder to redirect the logstash on the elastic search in that case also the host ip address will be used. Which is evident in the host of logstash.conf file.
