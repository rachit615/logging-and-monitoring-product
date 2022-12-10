# logging-and-monitoring-product

**Problem statement**
Monitoring and Logging of application in any environment like containerized environment, cluster and bare metal.​

Develop a logging and monitoring utility mode to enhance the output of  which can monitor and observe the application.​

**Objectives**

To make a solution which can monitor and observe the application.​

To create a centralized logging solution where we can collect all the logs from different containers and analyse the logs.​

To examine the metrics produced by the containers effectively.​

To monitor and observe the application in any environment like containerized environment, cluster and bare metal.​

Assessing application health and troubleshooting.​

Diagnosing and identifying the root cause of application installation and run-time errors.​

We will deploy ansible playbooks and docker compose files to deploy our solutions.​

**steps to deploy ELK stack:-<br />**
<br />

1.clone this repository.<br />
2.start the containers by using  docker-compose up -d   command <br />
3.update the logstash.conf file by providing the correct IP with specified port i.e 9200 for elasticsearch. <br />
4.now to test our setup start an additional nginx container using docker CLI. <br />
5.Access kibana at specific IP with specified port i.e 5601. <br />
6.create index pattern using * and @timestamp <br />
7.now we can see logs of out nginx and apache container. <br />

