# Term-docker-compose
collect docker-compose for termWork!

###How to run?

- At first or want to rebuild:

> docker-compose -f application.yml up -d

- Next time:

> docker-compose -f application.yml start

- Stop service:

> docker-compose -f application.yml stop


###Instruction

####application.yml

- mediawiki run on 0.0.0.0:10080 [wikimedia/mediawiki](https://github.com/wikimedia/mediawiki)

- weinre run on 0.0.0.0:8080
[pmuellr/weinre](https://github.com/pmuellr/weinre)

####gitlab.yml
- gitlab run on 0.0.0.0:13080


####libreboard.yml
- libreboard run on 0.0.0.0:15080
[libreboard/libreboard](https://github.com/libreboard/libreboard)

####monitor.yml
- cadvisor run on 0.0.0.0:11080
[google/cadvisor](https://github.com/google/cadvisor)




