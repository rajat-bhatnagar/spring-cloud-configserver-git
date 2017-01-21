# spring-cloud-configserver-git
Spring Cloud Config server which pulls properties from another git repository (https://github.com/rajat-bhatnagar/spring-cloudconfig-wa-tolls)

- For an invalid property name like s2rates-rajat which does not exist we just get back the default response from application.yml, We can also get the information in a particular format like json, yml, properties , env specific etc..
<i>URI s for pulling remote git properties information</i><br>
<i><a href="http://localhost:8888/s2rates-rajat.yml">http://localhost:8888/s2rates-rajat.yml</a></i><br>
<i><a href="http://localhost:8888/s2rates-default.json">http://localhost:8888/s2rates-default.json</a></i><br>
<i><a href="http://localhost:8888/s1rates-default.properties">http://localhost:8888/s1rates-default.properties</a></i><br>
<i><a href="http://localhost:8888/s2rates/qa">http://localhost:8888/s2rates/qa</a></i><br>
<i><a href="http://localhost:8888/s1rates/dev">http://localhost:8888/s1rates/dev</a></i><br>

