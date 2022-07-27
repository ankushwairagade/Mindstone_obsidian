YAML is a human-readable data-serialization language. It is commonly used for configuration files and in applications where data is being stored or transmitted. YAML targets many of the same communications applications as Extensible Markup Language but has a minimal syntax which intentionally differs from SGML


YAML = YAML ain't markup language

-- Data format used to exchange data
-- Simnilar to XML and Json
-- In YAML, you can store only data, nad not commands

Data Serialisation :
	Data serialization is the process of converting data objects present in complex data structures into a byte stream for storage, transfer and distribution purposes on physical devices.
	
	![[Pasted image 20220506180332.jpg]]



Without being exhaustive, here are some common ones:[](https://devopedia.org/data-serialization#Reitz-and-Schlusser-2020 "Reitz and Schlusser 2020") [](https://devopedia.org/data-serialization#Wikipedia-2020b "Wikipedia 2020b")

-   **XML (Extensible Markup Language)** - Nested textual format. Human-readable and editable. Schema based validation. Used in metadata applications, web services data transfer, web publishing.
-   **CSV (Comma-Separated Values)** - Table structure with delimiters. Human-readable textual data. Opens as spreadsheet or plaintext. Used as plaintext Database.
-   **JSON (JavaScript Object Notation)** - Short syntax textual format with limited data types. Human-readable. Derived from JavaScript data formats. No need of a separate parser (like XML) since they map to JavaScript objects. Can be fetched with an `XMLHttpRequest` call. No direct support for `DATE` data type. All data is dynamically processed. Popular format for web API parameter passing. Mobile apps use this extensively for user interaction and database services.
-   **YAML (YAML Ain't Markup Language)** - Lightweight text format. Human-readable. Supports comments and thus easily editable. Superset of JSON. Supports complex data types. Maps easily to native data structures. Used in configuration settings, document headers, Apps with need for MySQL style self-references in relational data.


YAML Used in Docker / Kubernetes / logs / Caches /etc /
Benefits of YAML
	- Simple and Easy to read
	- It has a strict syntax {Indentation is important}
	- Easily convertable to Json , XML
	- Most lang use YAML
	- more powerful when Representation complex Data
	- Parsers , etc various tools available { Lens , Monokle , Datree ...}
	- YAML is Case Sensitive 

Data 
Key value Pair 
	"Key" : " value"
	 1 : "value"

List / Dictionaries
 lists :
  -apple
  -mango
  -banana
  -Apple

