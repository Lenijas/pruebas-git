# pruebas-git
repositorio para probar las funcionalidades de github
Probando md

#otro titulo 
~~Tachado~~
**Bold**

```
for ele in list:
  print ele
```



**Python**

	@requires_authorization
	def somefunc(param1='', param2=0):
	    r'''A docstring'''
	    if param1 > param2: # interesting
	        print 'Gre\'ater'
	    return (param2 - param1 + 1) or None

	class SomeClass:<br>    pass

	>>> message = '''interpreter
	... prompt'''

**XML**

	<?xml version="1.0"?>
	<response value="ok" xml:lang="en">
	  <text>Ok</text>
	  <comment html_allowed="true"/>
	  <ns1:description><![CDATA[
	  CDATA is <not> magical.
	  ]]></ns1:description>
	  <a></a> <a/>
	</response>
	

**Markdown**

	# hello world

	you can write text [with links](http://example.com).

	* one _thing_ has *em*phasis
	* two __things__ are **bold**

	---

	hello world
	===========

	<this_is inline="xml"></this_is>

	> markdown is so cool

	    so are code segments

	1. one thing (yeah!)
	2. two thing `i can write code`, and `more` wipee!

forzando hook11

 ```

 javascript
    sdk = new AeonSDK(channel.PUB_URL);
    msg = { "number": 1};
    sdk.publish(msg);
```


    
http://<tomcat>:8080
(<http://localhost:8080/>) this means



#### Companies

  Name                 Verb     URL
  -------------------- -------- ---------------------------
  Get Company          GET      /v1/companies/{companyId}
  Get Companies List   GET      /v1/companies/
  Create Company       POST     /v1/companies
  Upsert Company       PUT      /v1/companies/{companyId}
  Delete Company       DELETE   /v1/companies/{companyId}


Add new items as a last items under each section. In example put below
\<dependency\> as a last dependency definition in the pom.xml


[Apache Maven](https://maven.apache.org/index.html), or other building
tools are necessary to create the final WAR package that will run on
Tomcat.\
We can also suggest to build the WAR package by using your favorite IDE
(which should include Maven).


adsfadfa
adsfasdfadsf




check that all processes are up, to check it execute

```
ps -ef | grep iot
```
- If the iot agent is active, the following processes should be active:
```
iotagent 19682     1  0 10:32 ?        00:00:00 /usr/local/iot/bin/iotagent -n IoTPlatform -v INFO -i 192.0.3.25 -p 8080 -d /usr/local/iot/lib -c /etc/iot/config.json
```
- If storage type is "mongodb" you need a mongodb database up.   
``` 
mongod    1173     1  0 Jul09 ?        08:55:40 /usr/bin/mongod -f /etc/mongod.conf
```
- If the MQTT protocol is active, the following processes should be active:  Mosquitto
```
root      8098     1  0 Jul13 ?        00:47:26 /usr/sbin/mosquitto -c /etc/iot/mosquitto.conf
``` 
- If the IoT Manager module  is active, the following processes should be active: MongoDB
```
iotagent 20291     1  0 Sep24 ?        00:00:42 /usr/local/iot/bin/iotagent -m -n Manager -v INFO -i 192.0.3.25 -p 8081 -d /usr/local/iot/lib -c /etc/iot/config.json

```
	asdasdfasdfasdfa



asdfadfasdfad


- Item 1
```
code 1
```
- Item 2
    ```
    code 2
    
    code 2.1
    ```



## License

This specification is licensed under the
[FIWARE Open Specification License (implicit patent license)]
(https://forge.fiware.org/plugins/mediawiki/wiki/fiware/index.php/Implicit_Patents_License).
