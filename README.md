# Semantic Web Exercise

This project demonstrates the use of RDFa (Resource Description Framework in Attributes) to create a personal FOAF (Friend of a Friend) profile using Linked Data principles.

## Files
- `index.html`: Main HTML file containing a personal profile with RDFa markup

## Usage
1. Open `index.html` in a web browser to view the profile
2. Examine the source code to see how RDFa attributes are used to add semantic meaning
3. Use an RDFa validator/extractor (like https://www.w3.org/2012/pyRdfa/) to extract the embedded RDF data

## RDFa Concepts Used
- Namespaces: FOAF, RDFS, Schema.org
- Properties: name, nick, mbox, homepage, etc.
- Resources: References to DBpedia for linking interests to the Semantic Web

## Viewing the RDF Data
To extract and view the RDF data embedded in the HTML:
1. Visit an online RDFa extraction tool
2. Input the HTML content or link to your published page
3. Extract the data in your preferred RDF serialization format (RDF/XML, Turtle, etc.)

## Resources
- FOAF Vocabulary Specification: http://xmlns.com/foaf/spec/
- RDFa Primer (Social Networks section): https://www.w3.org/TR/rdfa-primer/#exploring-further-social-networks
- EasyRDF Converter for RDFa validation: http://www.easyrdf.org/converter 