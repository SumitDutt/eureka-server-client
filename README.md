Ereka-Serverr details </br>

http://localhost:8761/</br>
spring.application.name=service-registry</br>
server.port = 8761</br>
eureka.client.register-with-eueka=false</br>
eureka.client.fetch-registery=false</br>


<properties></br>
<java.version>21</java.version></br>
<spring-cloud.version>2024.0.0</spring-cloud.version></br>
</properties></br>

</br></br>
<dependency></br>
<groupId>org.springframework.cloud</groupId></br>
<artifactId>spring-cloud-starter-netflix-eureka-server</artifactId></br>
</dependency></br>

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
