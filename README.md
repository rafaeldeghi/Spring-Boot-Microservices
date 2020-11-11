# Spring-Boot-Microservices usando Eureka

- Criar 3 Spring Boot projects {
	- Criar um service API de catalogo de filmes
	- Criar um service API de Detalhes do Filme
	- Criar um service API de Notas do Filme
  
  Microservices {
	
	Service de Nota dos Filmes{
		Input:UserID
		Output:FilmeID E Notas
	}	

	Service Detalhes dos Filmes{
		Input: FilmeID
		Output: Filme com Detalhes
	}

	Service Catalogo de Filmes{
		Input: UserID
		Output: Lista de Filmes com Detalhes
	};
}

Portas: 8081: movie-catalog-service,
	      8082: movie-info-service,
	      8083: ratings-data-service
        8761: spring-eureka
