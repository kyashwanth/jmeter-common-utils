# jmeter-common-utils



# Common Issues and solutions
1. If encountering outof Heap exceptions use
    > java -Xms1G -Xmx3G -jar ApacheJMeter.jar "regular params of jmeter"

2. If jtl file is not being written then use 
    > -Jjmeter.save.saveservice.autoflush=true
