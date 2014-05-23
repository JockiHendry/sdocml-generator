sdocml-generator
================

Requirement
-----------
Java 7 and Groovy


Quick Start
-----------
To generate jQuery SDOCML based on the latest documentation in http://api.jquery.com/resources/api.xml, use the following command:

     groovy generate-jquery -url -output jquery.sdocml

To generate jQuery SDOCML based on XML file that has the same structure with jQuery API documentation XML reference, use the following command:

     groovy generate-jquery -file jquery-api-sample.xml -output jquery.sdocml