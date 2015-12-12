# ecommerce-testing-project7
jmeter -n -t Project7LoadRelatedProducts2.jmx -Jhost.ip=localhost -Jhost.port=80 -Jfilename=relatedProducts

jmeter -n -t Project7LoadUsers.jmx -Jhost.ip=localhost -Jhost.port=80 -Jfilename=loadUsers
 
jmeter -n -t Project7.jmx -Jhost.ip=ecommerce-loadbalancer-293335628.us-east-1.elb.amazonaws.com -Jhost.port=80 -Jfilename=test1
