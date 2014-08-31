index
=====

The Index Repository


## Coding and Code Running:
dockerimages/ruby:2
dockerimages/ruby:1.9
dockerimages/go
dockerimages/php


## Servers
dockerimages/hipache
dockerimages/redis
dockerimages/redmine
dockerimages/apache2
dockerimages/php5-fpm             = PHP5 Server you need to start it with volumes from else it can't work ;)
dockerimages/interspeed:lvl1      = Interspeed Project
dockerimages/solr                 = supplys solr
dockerimages/couchbase:2.5.1
dockerimages/openproject
dockerimages/wordpress            = supplys mysql+joomla+apache2-mod-php5
dockerimages/joomla3              = supplys mysql+joomla+apache2-mod-php5
dockerimages/joomla3:main         = uses mysql external and php5 external
dockerimages/mysql:5.5            = supplys mysql
dockerimages/haproxy              = supplys haproxy
dockerimages/shipyard             = deploys the docker webui from shipyard


## Application Packages
dockerimages/frank-scripts        = updates and installs franks scripts
dockerimages/cbfs
dockerimages/nsenter
dockerimages/builddocker
dockerimages/build-go
dockerimages/mysql-cli
