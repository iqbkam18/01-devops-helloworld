# 01-devops-helloworld

I ukene som kommer skal vi jobbe med DevOps relaterte verktøy og software. For at første praktiske oppgave som skal gjøres på forelesning #2 skal bli så effekitv som mulig er ukens oppgave som følger

* Registrer konto, og bli kjent med https://travis-ci.org/ - vi skal bruke Travis for kontinuerlig integrasjon og kontinuerkig leveranse
* Sørg for at Docker kjører bra på din maskin  

# Arbeidsoppgaver for Første øving

* Lag et nytt repository på github. 

* I repoet; Lag en ny Javaapplikasjon du kan jobbe videre med i løpet av høsten. Du kan gjerne bruke verktøyet https://start.spring.io/ - 
for å komme raskt i gang. Hvis du bruker Spring Init verktøyet, legg til avhenginghetene "web", "jpa" og kanskje "lombok" 

* Sørg for at applikasjonen bygger med mvn, og starter en webserver på localhost:8080


```sh
mvn spring-boot:run
````

* I de fire første forelesningene skal vi jobbe med "flow" - veien koden vår tar fra vi har skrevet den, til den oppleces av systemets brukere.
Et viktig verktøy for å få en smidig reise, er et godt vertkøy for det vi kaller CI og CD (Continous Integration, Continous delivery) 
Vi skal prate med om dette i neste forelesning, i dag skal vi sette opp vertøyet. 

* Målet er at Travis skal kjøre unit tester- og kompilere koden, hver gang vi gjør en push til master branch på github
for eksempel-applikasjonen vår. 

* Kom i gang med Travis for github; https://docs.travis-ci.com/user/tutorial/#to-get-started-with-travis-ci-using-github


* Bonusoppgaver 

* Registrer konto på heroku.com https://signup.heroku.com/

* Ta en kikk på hvordan man deployer spring boot applikasjoner til Heroku. 
https://devcenter.heroku.com/articles/deploying-spring-boot-apps-to-heroku


