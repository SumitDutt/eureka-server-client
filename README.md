# eureka-server-client know as service registry or sprig Discovery</br>
Spring Cloud Discovery (Eureka) Sever-client -> Service Registr</br>
<br></br>http://localhost:8761/</br></br>
spring.application.name=service-registry</br>
server.port = 8761</br>

eureka.client.register-with-eueka=false</br>
eureka.client.fetch-registery=false</br>

</br></br>
<dependency></br>
<groupId>org.springframework.cloud</groupId></br>
<artifactId>spring-cloud-starter-netflix-eureka-server</artifactId></br>
</dependency></br></br></br>

</br></br>
<dependencyManagement></br>
		<dependencies></br>
			<dependency></br>
				<groupId>org.springframework.cloud</groupId></br>
				<artifactId>spring-cloud-dependencies</artifactId></br>
				<version>${spring-cloud.version}</version></br>
				<type>pom</type></br>
				<scope>import</scope></br>
			</dependency></br>
		</dependencies></br>
	</dependencyManagement></br>
