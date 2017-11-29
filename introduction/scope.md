## Scope {#scope}

What does the Best Practices cover?

* [ ] Pointers to a CMDI introduction, the CMDI specification, …

The target audience for the Best Practice guide includes 1\) CMD modellers who select or create components and profiles to describe certain language resources, 2\) developers who create metadata converters, forms or editors to create records that comply with these profiles, and 3\) the group of CMD creators who create records "by hand", i.e. using no other tooling than an XML editor or even a plain text editor. End users of the infrastructure are, in general, not directly exposed to CMDI, but if so should be fully guided by a user-friendly interface \(with its own user guide\) and shielded from the technical details. Furthermore, using this Best Practice guide will require a basic understanding of CMDI - it is not intended as a tutorial.[^1]

The CLARIN infrastructure can deal with any valid CMD record that is based on a profile from its Component Registry. The technical specification \(CE-2016-0880\) acts as the core reference with its declarative definitions and examples of valid CMD profiles, components and records. In contrast, the CMDI Best Practice guide is process oriented and aims to guide the work involved in constructing valid and high quality CMD components, profiles and records. The scope of the best practices goes beyond those purely schematic constraints and ranges from modelling guidelines, e.g. "prefer elements over attributes", to rather low-level technical guidelines, e.g. "use the UTF-8 encoding for your CMD records". In general, the CLARIN infrastructure will extract information more efficiently from CMD records that meet these best practices and, hence, provide the end users improved access to those records, the context from which they originate and the resources they provide.

[^1]: For a tutorial, please refer to https://www.clarin.eu/cmdi\#training 

