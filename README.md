# XML (Extensible Markup Language) 

is used in web development for various purposes, including:

- **Data Storage and Transfer:** XML is commonly used to store and transport data between systems, especially in web services and APIs.

- **Configuration Files:** Many web applications and frameworks use XML for configuration settings (e.g., Spring Framework in Java, .NET applications).

- **Web Services (SOAP):** XML is the foundation of SOAP (Simple Object Access Protocol), which is used for exchanging structured information in web services.

- **RSS and Atom Feeds:** XML is used in RSS (Really Simple Syndication) and Atom feeds to structure and distribute web content like news and blog updates.

- **Sitemaps:** Search engines use XML sitemaps to understand the structure of a website and index its pages effectively.

- **Data Exchange Between Different Technologies:** XML is platform-independent, making it ideal for exchanging data between different programming languages and systems.

- **SVG (Scalable Vector Graphics):** XML-based SVG is used for creating vector graphics that can be scaled without losing quality.

- **XHTML:** An XML-based version of HTML that ensures stricter document structure and validation.

While JSON has largely replaced XML for data exchange in modern web applications due to its simplicity and efficiency, XML is still widely used in legacy systems and specific applications.


## Explanation of tech.xml

1. XML Declaration (< ?xml version="1.0" encoding="UTF-8"? >)

This specifies the XML version (1.0) and character encoding (UTF-8).

2. Root Element (< bookstore >)

The outermost element that contains all book records.

3. Child Elements (< book >)

Each <book> represents a book entry inside the bookstore.

4. Attributes (id="b1")

The id attribute uniquely identifies each book.

5. Nested Elements

< title >, < author >, and < price > define book details.

  6. Attribute in Element (< price currency="USD" >29.99< /price >)

The currency attribute specifies the currency type for the book price.
