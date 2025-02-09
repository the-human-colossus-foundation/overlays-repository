# Information Overlay

## Purpose

Information overlays purpose is to enahnce attributes with additional contextual information.

## Use cases

- For auditing, to better understand the context and ensure data integrity.
- To provide hints and real-time guidance for users filling out a form, reducing errors and confusion.
- To offer detailed, human-readable descriptions of attributes, improving accessibility.
- To assist in compliance with regulatory requirements by clearly explaining data fields.
- To support multilingual environments by providing explanations in different languages.
- To enhance user experience by providing tooltips or in-line explanations without cluttering the UI

## Specification

_[language-specific object]_

An Information Overlay defines attribute field descriptions and usage notes to assist the data entry process or to add context to presented data.

In addition to the [mandatory attributes](https://oca.colossi.network/specification/#mandatory-attributes) and `language` attributes (see [Common attributes](https://oca.colossi.network/specification/#common-attributes)), the Information Overlay MUST include the following attribute:

- `attribute_information`

   The `attribute_information` attribute maps key-value pairs where the key is the attribute name and the value is the informational prose in a specific language.


## Example

```json
{
   "capture_base":"EVyoqPYxoPiZOneM84MN-7D0oOR03vCr5gg1hf3pxnis",
   "type":"spec/overlays/information/1.0",
   "language":"en-UK",
   "attribute_information":{
      "dateOfBirth":"Holder’s date of birth as recorded by the issuing State or organization.",
      "documentNumber":"Unique identification number of the document.",
      "documentType":"The word for "passport" in the language of the issuing State or organization.",
      "fullName":"Full name of the passport holder.",
      "height":"Recorded height of the passport holder.",
      "issuingState":"Name of the State or organization responsible for issuing the passport.",
      "photoImage":"Portrait image of the passport holder.",
      "sex":"Sex of the passport holder."
   }
}
```

_Example 4. Code snippet for an Information Overlay (language: en_UK)._
