# dandanator-cpc
ROM assembler for the [CPC Dandanator Mini](http://www.dandare.es/Proyectos_Dandare/CPC_Dandanator%21_Mini.html).
An Amstrad CPC peripheral that allows for an easy and fast way to load snapshots in the machine.

This tool provides a way to create ROMSet compilations with our games of choose. Currently it supports games in SNA format.
Support for games in DSK and CDT format is also provided but still in beta stage.

## Requisites
Git, Maven and a JDK (11+ recommended; 17 works well with JavaFX 17) are needed.

##Cloning the repository
	git clone https://github.com/teiram/dandanator-cpc.git

## Building
Run the standard Maven build from the project root:

        cd dandanator-cpc
        mvn clean install

Maven will automatically select the right JavaFX artifacts for your platform, including Apple Silicon (`mac-aarch64`), macOS Intel, Windows, and Linux.

## Executing

An executable jar with all the dependencies bundled in will be generated in the following location:

    dandanator-cpc/target/dandanator-cpc-2.6.2-jar-with-dependencies.jar

Run it with:

        java -jar target/dandanator-cpc-2.6.2-jar-with-dependencies.jar

In most modern operating systems it should be also possible to execute the application by just double clicking on the jar file.
