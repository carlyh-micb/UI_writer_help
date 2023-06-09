# View Schema

This is a summary of the schema you have been creating. You can tab through mutliple languages (if you have more than one) to see all the schema information for each language.

To back and edit any of the entries use the back button to go through the schema writer and make your necessary changes.

When you Finish and Export your schema you will be able to download the "Excel Template" version of the OCA Schema.

# Parsing the Generated Excel Template

The Excel template with the schema information can be parsed into a machine actionable, standard representation of the schema called [Overlays Capture Architecture (OCA)](https://oca.colossi.network/).

The [SemanticEngine.org](https://www.semanticengine.org) website is where you will find the [XLS to OCA Converter](https://www.semanticengine.org/#/develop) which converts the Excel Template to the OCA Bundle.

The OCA Bundle contains the Capture Base and associated Overlays as files bundled into an archival (.zip) format.

You can open the archive and view the JSON code of the schema. The "meta.json" file lists is the most human readable and lists all Overlays and Capture Base including their SAID identifiers. 

# More information about OCA

## OCA is expressed in JSON
Overlays Capture Architecture is a machine-readable way to encode a schema expressed in the JSON scripting language. You can view the JSON file contents using a text editor such as Notepad in Windows but since JSON files do not usually contain line breaks it is easier to read using a [JSON viewer](https://jsonformatter.curiousconcept.com/) or in the JSON viewer when you [validate your schema bundle](https://www.semanticengine.org/#/validate).

## Advantages of OCA
The advantage of OCA schemas is that they are modular. You can start with a very simple design, and because of the OCA layered architecture you can add more functionality to the schema later. The simplest OCA schema has a Capture Base (CB) which defines the basic structure of the data, and some additional overlays (OL) that help the user understand the data. OCA schemas are also shareable and machine-readable. You can publish your OCA schema with an identifier and others can reference and extend your work.
