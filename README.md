# Cosmos DB NoSQL Highlighter

Enhance your Visual Studio Code experience with the NOSQL Syntax Highlighter for Azure Cosmos DB. 
This extension provides advanced syntax highlighting for NOSQL queries and commands used in Azure Cosmos DB, making it easier to work with your NoSQL data.

## Features

Key Features:
- Highlight keywords, operators, and functions specific to NOSQL in Azure Cosmos DB.
- Distinguish between strings, numeric values, and other data types for better readability.
- Increase efficiency with snippets.
- Easily identify comments and documentation in your NOSQL code.
- Improve code comprehension and reduce errors when working with Cosmos DB queries.

Get started with the NOSQL Syntax Highlighter and take your Cosmos DB development to the next level. Happy coding!

## Syntax highlighting
![Demo](media/vsCodeExtension.gif)

## Snippets using
### List of snippets:

**Code snippets:**
- select (select * from c where c.)
- insert (INSERT INTO c ({ "field1": "value1", "field2": "value2", "field3": "value3" }))
- update (UPDATE c SET c.field = "new value" WHERE c.id = @documentId)
- delete (DELETE FROM c WHERE c.id = @documentId)
- aggregate (SELECT COUNT(c) AS totalCount FROM c WHERE c.type = @docType)

![Demo](media/codeSnippets.gif)

**Stored procedure snippets:**
- storedPocedure (general stored procedure)
- creteCosmosDbItems (create documents to specific collection)

![Demo](media/storedProcedureSnippets.gif)

## Requirements
There are no specific requirements that the extension requires.

## Extension Settings
No special setting is required.


## Release Notes
Initial release of Cosmos DB NoSQL Highlighter Extension.

Initial release.

**Enjoy!**
