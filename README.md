# eureka-server-client know as service registry or sprig Discovery</br>
Spring Cloud Discovery (Eureka) Sever-client -> Service Registr</br>
In this module we Demo we have 4 module </br>
1. Service-Registry ------ Eureka-Server</br>
2. Company ---------------Eureka Client</br>
3. Job----------------------Eureka Client</br>
4. Review-------------------Eureka Client</br>
Here job Api inter connnect with Company and review  which is uuse COMPANY-SERVICE and REVIEW-SERVICE instrad of lochahost Socan dynamically move any where.</br>
return restTemplate.getForObject("http://COMPANY-SERVICE:8081/companies/" + companyId, Company.class);</br>
ResponseEntity<List<Review>> reviewRespose = restTemplate.exchange("http://REVIEW-SERVICE:8083/reviews?companyId=" + companyId, HttpMethod.GET, null, new ParameterizedTypeReference<List<Review>>() {});
        
