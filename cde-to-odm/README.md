## Introduction
This sub-directory includes the scripts for a pilot study for applying 
XSPARQL (https://www.w3.org/Submission/xsparql-language-specification/) to
convert RDF Turtle data into ODM XML data.

Tool from Semantalycs (https://github.com/semantalytics/xsparql) is employed to implement XSPARQL for data conversion.



## Implementation
Run

`java -jar cde-to-odm/xsparql-cli-jar-with-dependenar cde-to-odm/xsparql/cde-dob-to-odm.xsparql`

or 

`java -jar cde-to-odm/xsparql-cli-jar-with-dependenar cde-to-odm/xsparql/cde-sex-to-odm.xsparql`

respectively for "date of birth" and "sex".

