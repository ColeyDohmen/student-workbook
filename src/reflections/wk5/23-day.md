3/3/2021
Read Servers with Node/Express > MongoDb Relationships and answer the following questions
In simple terms what is a sub-document?
Subdocuments are documents that are nested within other documents.

When might you use a sub-document?
You use a subdocument when you want to nest a Schema within another Schema.

How do you add to a collection of sub-documents? What about editing them?
There are two ways to create documents that contain subdocuments, one is to pass a nested object into new model, the other is to add properties into the created document. The easiest way to update subdocuments is to Uuse findOne to find the document, then get the array, change the array, and run save.