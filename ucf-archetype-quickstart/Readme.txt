������д���
mvn ִ��java����
mvn exec:java -Dexec.mainClass="com.jhh.Main"
mvn exec:java -Dexec.mainClass="akka.Main" -Dexec.args="com.jhh.HelloWorld" 

mvn ִ��scala����
mvn scala:run -DmainClass=com.jhh.App -DaddArgs="arg1|arg2|arg3"