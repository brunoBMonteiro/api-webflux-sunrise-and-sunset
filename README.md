# api-webflux-sunrise-and-sunset
Reactive API with spring webflux, indicate latitude and longitude coordinates and receive sunrise and sunset information from the location.

API reativa com com spring webflux, indicar as coordenadas de latitude e longitude e receber informações do nascer e pôr do sol do local.

## User store / História de usuário

```Gherkin
Scenario: Get Location
  Given I've an address
  When I call the location service
  Then I should get a geo location
  And I should get the sunrise and sunset times
```

```Gherkin
Cenário: Obter localização
  Dado que eu tenho um endereço
  Quando ligo para o serviço de localização
  Então eu deveria obter uma localização geográfica
  E eu deveria ter os horários do nascer e do pôr do sol
```


## References / Referências

- https://spring.io/blog/2016/09/22/new-in-spring-5-functional-web-framework
- https://spring.io/blog/2017/02/23/spring-framework-5-0-m5-update
- http://junit.org/junit5/docs/current/user-guide/#running-tests-build-maven
- https://github.com/junit-team/junit5-samples
- https://developers.google.com/maps/documentation/geocoding/intro
- https://sunrise-sunset.org/api
- https://en.wikipedia.org/wiki/ISO_8601
