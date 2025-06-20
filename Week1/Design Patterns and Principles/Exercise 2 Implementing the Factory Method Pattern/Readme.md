Purpose:
Defines an interface for creating objects but lets subclasses alter the type of objects that will be created.

Used In:
FactoryMethodPatternExample.java

Technical Highlights:

Interface: Document with method like open() .

Concrete classes: WordDocument, PdfDocument, ExcelDocument.

Factories: WordDocumentFactory, PdfDocumentFactory, ExcelDocumentFactory that implement the createDocument() method.

Benefits:

Promotes loose coupling between client code and concrete classes.

Adds flexibility to introduce new document types without modifying existing code.