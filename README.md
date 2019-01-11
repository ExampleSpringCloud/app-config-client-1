- run <code>app-config</code> and <code>discovery</code> servers
- run this application  
<code>mvn spring-boot:run</code>
- go to http://localhost:8090/get-property
- to update properties  
<code>curl localhost:8090/refresh -X POST</code>