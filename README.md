# <a name="title"></a> chef-logstash [![Build Status](https://secure.travis-ci.org/lusis/chef-logstash.png?branch=master)](http://travis-ci.org/lusis/chef-logstash)

Description
===========

Cloudbau Logstash cookbook
it seems that logstash needs a lot of ressources, you should probably deploy it on a dedicated machine

Use
==========
- apply logstash server role to machine
- configured to get logs via syslog on port :5544 (use cloudbau rsyslog recipe)
- visit kibana on port 7000 and watch how the logs fly in