spring.application.name=company-service</br>
server.port = 8081/br>
eureka.client.serviceUrl.defaultZone=http://localhost:8761/eureka</br>
eureka.client.register-with-eueka=true</br>
eureka.client.fetch-registery=true</br>



<properties></br>
<java.version>21</java.version></br>
<spring-cloud.version>2024.0.0</spring-cloud.version></br>
</properties></br>

</br></br>
<dependency></br>
<groupId>org.springframework.cloud</groupId></br>
<artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>></br>
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
