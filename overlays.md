# Overlay Directory

Below is a table listing available overlays with their details:


Table consist of:
- `Name of overlay` - name as defined in overlayfile
- `Description` - short description explaining what is it's purpose
- `Example` - Link to example of such overlay
- `Depends on` - name of the object which this overlay depends on either `capture base` or another `overlay`
- `Status` - Proposed | Demonstrated | Accepted

## Core overlays

Core Overlays are defined directly by the [OCA
Specification](https://oca.colossi.network/specification/) and serve as the
foundational layer for working with OCA. They represent a de facto standard for
modeling data structures across diverse use cases. While each overlay is
designed for a specific purpose and no single set can cover all scenarios, core
overlays constitute the most widely adopted and interoperable subset within the
OCA ecosystem.

| Name of Overlay |  Description | Example | Depends on |
|---------------|-----------------------------|-------------|---------|
| Character Encoding | A character encoding overlay determines how numbers are assigned to graphical characters. | [Link](https://oca.colossi.network/specification/) | Capture base
| Format | A format overlay specifies the input and display formats for data fields. | [Link](https://oca.colossi.network/specification/) | Capture base
| Label | A label overlay defines the names of human-readable attributes. | [Link](https://oca.colossi.network/specification/) | Capture base
| Meta | A meta overlay defines any language-specific information relating to a schema. | [Link](https://oca.colossi.network/specification/) | Capture base
| Standard | A standard overlay is a documented agreement or technical specification published by a standards organisation that is used to represent, format, define, structure, tag, transmit, manipulate, use and manage data. | [Link](https://oca.colossi.network/specification/) | Capture base
| Cardinality | A cardinality overlay specifies the minimum and maximum number of values that an attribute can have. | [Link](https://oca.colossi.network/specification/) | Capture base
| Conformance | A conformance overlay shows whether data entry for each attribute is mandatory or optional. | [Link](https://oca.colossi.network/specification/) | Capture base
| Entry Code | An entry code overlay specifies the entry keys as a series of key-value pairs that are stored in a code table, also known as a 'lookup table', or a dataset. | [Link](https://oca.colossi.network/specification/) | Capture base
| Entry | An entry overlay specifies the values of an entry in the form of a series of key-value pairs, which are stored in a code table (also known as a 'lookup table') or dataset. | [Link](https://oca.colossi.network/specification/) | Entry Codes
| Unit | A unit overlay defines the units of measurement that are adopted by convention or law and used as a standard for measuring the same type of quantitative data. | [Link](https://oca.colossi.network/specification/) | Capture base
| Attribute mapping  | An attribute mapping overlay defines the mappings between the attributes of two distinct data models. | [Link](https://oca.colossi.network/specification/) | Capture base
| Entry Code Mapping | An entry code mapping overlay establishes the relationship between the entry keys in two distinct code tables or datasets. | [Link](https://oca.colossi.network/specification/) | Entry Codes
| Sensitive | A sensitive overlay is a specialised tool used to identify and flag attributes that require protection against unauthorised or unnecessary disclosure. | [Link](https://oca.colossi.network/specification/) | Capture base

## Community overlays

Below is a list of community developed overlays hosted in that repository

| Name of Overlay |  Description | Example | Depends on | Status
|---------------|-----------------------------|-------------|---------|------|
| Information | An Information Overlay defines attribute field descriptions and usage notes to assist the data entry process or to add context to presented data. | [Link](/overlays/0001-information/) | Capture base | Accepted
| Conditional | A Conditional Overlay defines conditional expressions (or rules) that trigger specific computations or actions depending on whether, upon evaluation, programmer-defined Boolean expressions return true or false values. | [Link](#) | Capture base | Proposed
| Unit Mapping | A Unit Mapping Overlay defines target units for quantitative data when converting between different units of measurement. | [Link](#) | Capture base | Proposed
| Presentation | Presentation overlays provide information to display digital documents at the application layer, including digital forms and credentials. | [Link](#) | Capture base | Proposed

Contributors are encouraged to update this table when submitting new overlays.
