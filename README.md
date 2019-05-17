TRoML
=====

The Textual Role Modeling Language (TRoML) is a simple textual modeling language to create instances of the CROM metamodel.

It is based on Xtext and depends on the definition of the CROM metamodel

## Prerequisits

* This project was developed and tested [*Eclipse Kepler for Java and DSL Tools*](http://www.eclipse.org/downloads/packages/eclipse-ide-java-and-dsl-developers/keplersr2)
     * *Version:* Kepler Service Release 2
     * *Build id:* 20140224-0627
* Please make sure that *Xtext 2.6.1* is present, if not pleace update the plugins via Eclipse 

## Installation

1. Clone the [CROM metamodel](https://github.com/Eden-06/CROM) as EMF Project "org.rosi.crom.metamodel" to your Eclipse Workspace.  
     Make sure to generate all files via the context menu within the genmodel viewer.
2. Add the **Xtext nature** to this Project via the context menu of the project folder, if not already added
3. Clone TRoML as Xtext Project to your Eclipse Workspace
4. Add the "org.rosi.crom.metamodel" project to the java build path of this project, if not already set
5. Run the GenerateTRoML.mwe2 file As MWE2 Workflow
