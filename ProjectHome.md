This project will contain code generation modules for NetBeans and Maven. Currently planned code generation modules are -
  1. toString() Generator for NetBeans
  1. Java Util Logger generator/user for NetBeans
    1. Generate Logger along with initializer and log method
    1. Add auto-log messages on certain places
      * Add Logs on the first line of Methods
      * Add Logs just before return statements
      * Add logs just before throw statements
      * Log exceptions in Catch block (Not started yet)
    1. Convert all System.out.print(ln) to Logger messages
  1. Add License Header (Not started yet)
  1. xml-2-properties plugin 4 Maven
    * This plugin will generate resource bundles in xml or properties format from a single xml file.

Once the NetBeans modules are completed they will be mavenizing them and at least 2 projects should generate from each one - mavenzed NB module and two - a maven plugin doing the same thing