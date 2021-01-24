# ReportISW2-ModuloSWTesting

## How To per l'esecuzione dei test per il progetto BookKeeper

Per eseguire i test generando solamente i report di JaCoCo, utilizzare il seguente comando:
```mvn clean verify ```
Il report è disponibile nella cartella `/bookkeeper/tests/target/site/jacoco-aggregate/`
Per eseguire i test generando anche il report del Mutation Testing di Pit, utilizzare il seguente comando:
```mvn clean verify -P pit-test```
Il report del Mutation Testing è disponibile nella cartella `/bookkeeper/bookkeeper-server/target/pit-reports/`

## How To per l'esecuzione dei test per il progetto OpenJPA

Per eseguire i test generando solamente i report di JaCoCo, utilizzare il seguente comando:
```mvn clean verify ```
Il report è disponibile nella cartella `/openjpa/tests/target/site/jacoco-aggregate/`
Per eseguire i test generando anche il report del Mutation Testing di Pit, utilizzare il seguente comando:
```mvn clean verify -P pit-test```
Il report del Mutation Testing è disponibile nella cartella `/openjpa/openjpa-kernel/target/pit-reports/`