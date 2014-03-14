Enable the Elasticsearch repos for Debian
=========================================

Reference: http://www.elasticsearch.org/blog/apt-and-yum-repositories/

Elasticsearch (the company) now  offers Debian repos for their products Elasticsearch and Logstash.
This role adds the repos and their public key.

You can either add both Elasticsearch and Logstash, or specify the variables
`use_elasticsearch: False` or `use_logstash: True` when including the role, to
only use that repo. By default use_elasticsearch is true, use_logstash is
false.
