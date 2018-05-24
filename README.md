# elasticsearch-apache-logs
apache logs analysis

Test logstash installed or not:
cmd promt .../bin>logstash -e 'input { stdin { } } output { stdout {} }'

Load data to Elastic search from txt file.
cmd promt .../bin>logstash -f 'D:\EMPID_6095812\ELK development\workspace\apachelogs\apache_logstash.conf'
