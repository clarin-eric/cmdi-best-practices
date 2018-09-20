**In many cases one has to model for uncertainty. For example, the creation date of a document may not be known or only by approximation. Rather than making a field for such information optional, it might be desirable to provide the metadata creator with an option to make this uncertainty explicit. A "string" typed field provides this option \(i.e. it allows the metadata creator to enter "?" or "unknown"\) but does so at the cost of value "safety" - in this example it does not enforce a standardised date format. A better approach is to require a value of a more specific type if applicable, for example a date or integer. Alternatively avocabularyorpatterncan be used to constrain the values that may be entered, optionally including a literal value like 'Unknown'. You can add an \(optional\) attribute with type "boolean" or a vocabulary to allow the metadata creator to specify the level of uncertainty.**

**  
**

**Note that in many cases making an element optional is a valid modelling decision for cases where information might not be available.**

  


