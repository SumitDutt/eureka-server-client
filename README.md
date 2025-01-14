Open-feign Details
<dependency></br>
<groupId>org.springframework.cloud</groupId></br>
<artifactId>spring-cloud-starter-openfeign</artifactId></br>
</dependency></br>
<br>
@SpringBootApplication</br>
@EnableFeignClients</br>
</br>
</br>
@FeignClient(name="COMPANY-SERVICE")</br>
public interface CompanyClient {</br>
   @GetMapping("/companies/{id}")</br>
   Company getCompany(@PathVariable Long id);</br>
}</br>
