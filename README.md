# What is Swagger UI
Swagger client/Swagger UI is a Open Source HTTP Client.This can be configured in application ontime that will scan all our controller classes and creates one dynamic UI which makes HTTP Request to test those method with input and display Final Response.

No need to enter URLs manually, no need to provide HTTP methods manually.Model class views given. Easy to execute, hide using Profiles.

Swagger Configuration output is Docket(Documented Configured Output).
We must provide input of common package name for all RestController to scan them using
.apis(basePackage(--------))
with condition having one common path 
.paths(regex("_____")
dot(.) - character  Star(*) - zero to many
/rest.* => starts with /rest and may contain zero to many other chars

# Dependency
```
pom.xml
		<dependency>
			<groupId>io.springfox</groupId>
			<artifactId>springfox-swagger-ui</artifactId>
			<version>2.9.2</version>
		</dependency>

		<dependency>
			<groupId>io.springfox</groupId>
			<artifactId>springfox-swagger2</artifactId>
			<version>2.9.2</version>
		</dependency>
```
