# java-client

For more details, please check:  https://access.redhat.com/solutions/973783

for instance: 

'''java
java -Djavax.net.debug=ssl:handshake:verbose:keymanager:trustmanager -Djava.security.debug=access:stack  JavaHttpsClient https://200.1.124.118/PSEWebServices3/MainServices.asmx 1
'
