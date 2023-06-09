# Attribute Details

On the attribute details page you can edit properties of each attribute present in your schema.

# Attribute Name
You can edit each attribute name, and reorder the attributes.

# Flagged
Flagged attributes are where you can specify Flagged Attribute for sensitive data (e.g. names of people, government identification, birth date etc.). Marking an entry with a check will allow you to flag any attributes where identifying information about entities may be captured. 

Flagging an attribute acts as an alert to data users to treat the data as high-risk throughout the data lifecycle and encrypted or removed at any stage.

# Unit
Units are where you can describe the units for each attribute if needed.

# Type
* Text: text, from single letter entries to fields of unstructured text.
* Numeric: numbers
* Reference: A SAID identifier
* Boolean: a data type where the data only has two possible variables: true or false.
* Binary: a data type that defines a binary code signal
* DateTime: a data type that defines dates. Common formats include dates (e.g., YYYY-MM-DD), times (e.g., hh:mm:ss), dates and times concatenated (e.g., YYYY-MM-DDThh:mm:ss.sss+zz:zz), and durations (e.g., PnYnMnD).
* Array [attribute type]: a data type that defines a structure that holds several data items or elements of the same data type.

# List

A list is a very useful feature that allows the schema author to limit the data that can be entered for a specific attribute. Select this option if you would like to create a list of acceptable entries that the user will be able to select from.

It the user is able to select only one valid entry from the list (e.g. a list where the user will select the sample location), your data Type will be something suitable like "Text" or "Numeric". If you will allow multi-selection from the list (e.g. a list where the user can select all that apply) then your data Type is an Array.

