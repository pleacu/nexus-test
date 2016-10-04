# nexus-test
Nexus load-balancer test.

# To create components in https://origin-repository.jboss.org/nexus
cd create-test-tp
mvn clean deploy

# To reference components in https://repository.jboss.org/nexus
cd ref-test-tp
mvn clean install
