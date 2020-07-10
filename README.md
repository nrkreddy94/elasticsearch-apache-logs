# Elasticsearch Apache Logs

### Apache Logs Analysis

We have Apache server logs as data set with .txt file format ( apache_logs.txt ). We will convert this text format data set to json data with logstash as the repo Elasticsearch accepts only json format input. This process script available in the file "apache_logstash.conf". 

Apache server logs format as below:

```
83.149.9.216 - - [17/May/2015:10:05:03 +0000] "GET /presentations/logstash-monitorama-2013/images/kibana-search.png HTTP/1.1" 200 203023 "http://semicomplete.com/presentations/logstash-monitorama-2013/" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/32.0.1700.77 Safari/537.36"
```

The logstash file input is text file and output is ElasticSearch means convert txt file data to json format then push this data to elasticsearch with  template "apache_template.json". we use this template to map our json data properties to elastic search datatypes.


#### Dashboard view 1
 ![dashboard_1](/dashboard_1.PNG)

 #### Dashboard view 2
 ![dashboard_2](/dashboard_2.PNG)

 #### Dashboard view 3
 ![dashboard_3](/dashboard_3.PNG)



### Useful Links

[Elasticsearch MyBook](https://github.com/nrkreddy94/elasticsearch-mybook)

[ELK MyCollection](https://github.com/nrkreddy94/elasticsearch-repo)

[RPA UIPath ElasticSearch](https://github.com/nrkreddy94/RPA_UIPath_ElasticSearch)

[ELK Paris Accidenthology](https://github.com/nrkreddy94/elasticsearch-paris-accidentholgy)

[ELK Json Logs](https://github.com/nrkreddy94/elasticsearch-logstash-jsonlog)