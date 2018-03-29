# macOS-Unified-Logging: Filters

The filters are defined using Cocoa predicates, which you can read more about here: [Predicate Programming Guide](https://developer.apple.com/library/content/documentation/Cocoa/Conceptual/Predicates/AdditionalChapters/Introduction.html)

* [Pattern]()
* [Operator]()
* [Examples]()

## Pattern

* [eventMessage]()
* [processImagePath]()
* [senderImagePath]()
* [subsystem]()
* [category]()
* [eventType]()
* [messageType]()

#### eventMessage

#### processImagePath

#### senderImagePath

#### subsystem

#### category

#### eventType

#### messageType

## Operator

* **==** (or **=**) for equality
* **!=** or **<>** for inequality
* **>=** or **=>** for greater than or equal to
* **<=** or **=<** for less than or equal to
* **>** for greater than
* **<** for less than
* **AND** or **&&** for logical and
* **OR** or **||** for logical or
* **NOT** or **!** for logical not
* **BEGINSWITH**, **CONTAINS**, **ENDSWITH**, **LIKE**, **MATCHES** for string comparisons, using regex expressions when desired; strings can be compared with case insensitivity and diacritic insensitivity by appending [cd] to the operator, e.g. CONTAINS[c] means case-insensitive comparison
* **UTI-CONFORMS-TO**, **UTI-EQUALS** support comparison of UTIs like com.adobe.pdf
* **ANY**, **SOME**, **NONE**, **IN**, and array operators are available but unlikely to be used
* **FALSE**, **TRUE**, **NULL** have their expected literal meanings.

## References

[log: a primer on predicates](https://eclecticlight.co/2016/10/17/log-a-primer-on-predicates/)
