# Dama italiana [![CI/CD](https://github.com/softeng2021-inf-uniba/progetto2021ter-vijayashanker/actions/workflows/ingsw2021.yml/badge.svg)](https://github.com/softeng2021-inf-uniba/progetto2021ter-vijayashanker/actions/workflows/ingsw2021.yml) [![Coverage Status](https://coveralls.io/repos/github/softeng2021-inf-uniba/progetto2021ter-vijayashanker/badge.svg?t=aUA7xi&service=github)](https://coveralls.io/github/softeng2021-inf-uniba/progetto2021ter-vijayashanker)


La struttura della repository si presenta nel seguente modo:
```
|-- .github
|    |-- workflows
|    |      |-- ingsw2021.yml
|-- build
|    |-- reports
|    |      |-- checkstyle
|    |      |-- spotbugs
|    |      |-- jacoco/tests
|    |      |-- tests/test
|–– config
|    |–– checkstyle
|–– doc
|    |–– drawings
|    |–– javadoc 
|    |–– Report.md
|–– gradle
|–– lib
|–– res
|–– src
|    |–– main
|    |–– test
|–– .gitignore
|–– build.gradle
|–– Assegnazione progetto.md
|–– Guida per lo studente.md
|–– README.md
|–– gradlew
|–– gradle.bat
|–– settings.gradle
```

Nel seguito si dettagliano i ruoli dei diversi componenti:
- **.github/workflows/ingsw2021.yml**: dettaglia le direttive per assicurare la *continuous integration* attraverso l’uso di GitHub Actions;
- **build**: ospita la sottocartella *reports*, contenente gli output dei tool automatici di test e controllo di qualità;
- **config**: ospita i file di configurazione. L’unica configurazione di base richiesta è quella per il tool checkstyle;
- **doc**: in questa cartella deve essere inserita tutta la documentazione relativa al progetto. In particolare, in *drawings* dovranno essere salvati i diagrammi UML e *javadoc* ospiterà la documentazione generata automaticamente per il codice Java. Il file *Report.md* rappresenta la relazione finale del progetto;
- **gradle**: contiene il jar per il sistema di gestione delle dipendenze *Gradle*.
- **lib**: creata per includere eventuali *jar* di librerie esterne utilizzate dal progetto.
- **res**: la cartella deve contenere tutte le risorse usate dal sistema (immagini, testi ecc.)
- **src**: la cartella principale del progetto, in cui scrivere tutto il codice dell’applicazione. In *main* ci saranno i file sorgente e *test* conterrà i test di unità previsti.
- **.gitignore**: specifica tutti i file che devono essere esclusi dal sistema di controllo versione.
- **build.gradle**: esplicita le direttive e la configurazione per *Gradle*. 
- **Assegnazione progetto.md**: fare riferimento a questo file per la descrizione dettagliata del progetto assegnato;
- **Guida per lo studente.md:** elenca e descrive tutti i passi di configurazione necessari per attivare l’intero flusso di lavoro dietro lo sviluppo del progetto;
- **gradlew & gradlew.bat**: sono i file eseguibili di *Gradle*, rispettivamente per Unix e per Windows. Vengono generati automaticamente da Eclipse;
- **settings.gradle**: file di configurazione di *Gradle*. Anche quest’ultimo viene generato automaticamente da Eclipse.

In alcune cartelle è possibile notare la presenza di un unico file nascosto `.keep`: questo ha il solo scopo di richiedere a Git l’inclusione delle cartelle in cui è contenuto (Git esclude dal *versioning* le cartelle vuote). Pertanto, il file può essere ignorato o eventualmente cancellato nel momento in cui si inserisca almeno un altro file all’interno della cartella.


# Italian Checkers [![CI/CD](https://github.com/softeng2021-inf-uniba/progetto2021ter-vijayashanker/actions/workflows/ingsw2021.yml/badge.svg)](https://github.com/softeng2021-inf-uniba/progetto2021ter-vijayashanker/actions/workflows/ingsw2021.yml) [![Coverage Status](https://coveralls.io/repos/github/softeng2021-inf-uniba/progetto2021ter-vijayashanker/badge.svg?t=aUA7xi&service=github)](https://coveralls.io/github/softeng2021-inf-uniba/progetto2021ter-vijayashanker)


The repository structure is as follows:
```
|-- .github
|    |-- workflows
|    |      |-- ingsw2021.yml
|-- build
|    |-- reports
|    |      |-- checkstyle
|    |      |-- spotbugs
|    |      |-- jacoco/tests
|    |      |-- tests/test
|–– config
|    |–– checkstyle
|–– doc
|    |–– drawings
|    |–– javadoc 
|    |–– Report.md
|–– gradle
|–– lib
|–– res
|–– src
|    |–– main
|    |–– test
|–– .gitignore
|–– build.gradle
|–– Assegnazione progetto.md
|–– Guida per lo studente.md
|–– README.md
|–– gradlew
|–– gradle.bat
|–– settings.gradle
```

The roles of the different components are detailed below:
- **.github/workflows/ingsw2021.yml**: details the directives to ensure *continuous integration* through the use of GitHub Actions;
- **build**: hosts the *reports* subfolder, containing the outputs of the automatic testing and quality control tools;
- **config**: hosts the configuration files. The only basic configuration required is for the checkstyle tool;
- **doc**: all the documentation relating to the project must be inserted in this folder. In particular, the UML diagrams must be saved in *drawings* and *javadoc* will host the documentation automatically generated for the Java code. The *Report.md* file represents the final report of the project;
- **gradle**: contains the jar for the *Gradle* dependency management system.
- **lib**: created to include any *jar* of external libraries used by the project.
- **res**: the folder must contain all the resources used by the system (images, texts etc.)
- **src**: the main folder of the project, where to write all the application code. In *main* there will be the source files and *test* will contain the planned unit tests.
- **.gitignore**: specifies all the files that must be excluded from the version control system.
- **build.gradle**: specifies the directives and configuration for *Gradle*.
- **Project assignment.md**: refer to this file for the detailed description of the assigned project;
- **Student guide.md:** lists and describes all the configuration steps needed to activate the entire workflow behind the development of the project;
- **gradlew & gradlew.bat**: these are the executable files of *Gradle*, for Unix and Windows respectively. They are automatically generated by Eclipse;
- **settings.gradle**: *Gradle* configuration file. This one is also automatically generated by Eclipse.

In some folders you can notice the presence of a single hidden file `.keep`: this has the sole purpose of asking Git to include the folders in which it is contained (Git excludes empty folders from *versioning*). Therefore, the file can be ignored or possibly deleted when you insert at least one other file inside the folder.
