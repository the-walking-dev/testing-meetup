# Testing Meetup

El objetivo de este repo es almacenar ideas, documentos, PoCs, etc, para un posible meetup sobre testing (arquitecturas, prácticas, herramientas, etc).


## Ideas

Posibles temas a tratar:

  - Definición de los tipos de test:
    - Unitarios.
    - Integración.
    - Aceptación.
    - End to end.
    - Humo.
    - ¿otros?
  - Definición de tipos de arquitecturas:
    - Layered/n-tier.
    - Event-driven.
    - Microservices.
    - ¿otras? (microkernel, space-based, etc).
  - ¿Son las necesidades de test iguales para todos los modelos arquitectónios?
  - Que es aplicación y que es configurración ¿Se han de probar las configuraciones?
  - ¿Se han de "probar" los entornos?
  - Testing y su impacto en metodologías de desarrollo
    - TDD
    - BDD
  - Testing, procesos de desarrollo y CI/CD
    - Diferentes fases en las que ejecutar los tests:
      - IDE durante el desarrollo?
      - CI en cada commit antes de pasar a máster?
      - CI al mezclar con máster?
      - Nightly?
      - Antes de release?
      - Al desplegar?
      - En producción?
    - Cómo elegir los tests que deben ejecutarse en cada fase?
    - Comunicación de los resultados de los tests?
      - Radiadores / Monitores?
      - Correos?
      - Sólo código de máster? Cada commit?
      - Cómo tratar las regresiones?
    - Tests no funcionales en la vida real
      - Tools?
      - Tipos de tests?
        - Carga de aplicaciones web simulando usuarios y midiendo tiempos de respuesta?
        - Regresiones en tests no funcionales?
        - Cuándo se ejecutan estos tests?
      - Testing en DevOps
      - Cómo se verifica que CI funciona como se espera?
    - Testing Tools
- Calidad de los tests
  - Criterios basados en cobertura (por línea, función, rama,...). ¿Son todos igual de válidos?
  - Tests de mutación
  - Fault injection

## Eventos sobre testing y QA

### Conferencias

- España
  - ExpoQA: http://www.expoqa.com
  - VLCTesting: http://www.vlctesting.es/
  - QATest: http://www.qatest.org
- Europa
  - Ministry of Testing: https://www.ministryoftesting.com/
  - European Testing Conference: http://europeantestingconference.eu
- Resto del mundo
  - JenkinsWorld: https://www.cloudbees.com/jenkinsworld/home

### Meetups

 - MadQA: https://www.meetup.com/es-ES/MADQA-Grupo-Meetup-de-QA-y-TESTING-de-SOFTWARE-en-Madrid/
 - SevillaQA: https://www.meetup.com/es/SevillaQA/
 - BarcelonaTesters: https://www.meetup.com/es-ES/BarcelonaTesters/
 - BarcelonaQA: https://www.meetup.com/es-ES/Barcelona-QA-Meetup/
 - Barcelona Bugbusters: https://www.meetup.com/es-ES/Barcelona-Bugbusters-Meetup/

## Referencias interesantes

 - Blog con un post semanal recopilando novedades en el mundo del testing: https://www.petrikainulainen.net/weekly/
 - Reflexiones sobre los tests: http://www.lihaoyi.com/post/PrinciplesofAutomatedTesting.html
 - Post sobre sistemas resilientes con referencias actualizadas: http://www.panel.es/?p=30521
 - Testing de microservicios (blog de Martin Fowler): https://martinfowler.com/articles/microservice-testing/


## TODO

[ ] Definir lugar

[ ] Definir fecha
