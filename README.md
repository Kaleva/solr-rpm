Simple utility for creating an RPM for Solr.

Installs nicely with Tomcat 6, e.g.:

# yum -y install tomcat6
# yum -y install solr....rpm
# cp schema.xml /var/lib/solr/conf/
# service tomcat6 start
# chkconfig tomcat6 on

And you're ready to start indexing stuff.
