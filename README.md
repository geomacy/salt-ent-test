# Classic Models Database

This is an example for the Community [Blueprint Repository](http://blueprints.cloudsoft.io/) of how to install a database 
(MySQL in this case) using Brooklyn's [Salt support](https://brooklyn.apache.org/v/latest/yaml/salt).

It demonstrates a blueprint that uses the SaltEntity to install MySQL very simply using the [formula from 
SaltStack](https://github.com/saltstack-formulas/mysql-formula). To this is added a custom formula that installs
a database of choice (in this case the Classic Models database from http://www.mysqltutorial.org/mysql-sample-database.aspx),
and some pillar data to configure it.





