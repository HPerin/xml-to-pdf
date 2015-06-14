# xml-to-pdf

This is a library to convert data xml into a more readable format.

To use it it is very simple, you just need to add the jar to your classpath and use it like this:

```
Pdf pdf = new Pdf(filename);
pdf.fromXml(xmlString);
```