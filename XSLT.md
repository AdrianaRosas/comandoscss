##eXtensible Stylesheet Language Transformation

XSLT es un lenguaje de programación que se espresa en XML y puede tener diferentes funciones: 
1. Transformar de un formato a otro, por ejemplo, de un fichero XML-TEI a uno en (X)HTML, o incluso a Markdown. 
2. Interrogar los documentos XML y extraer informaciones. Por ejemplo, si queremos saber cuántos personajes hay, o las veces que habla nuestro personaje. Además, podemos extraer los nombres de los personajes, para crear nuestros índices. 

###Conceptos básicos
- Formato de entrada vs Formato de salida
- Parsear el documento
- Nodo contexto - Estructura arbórea
- Regla / Template

###Templates / Reglas 
`<xsl:stylesheet> </xsl:stylesheet>`
`<xsl:template match="nombre_del_elemento"> </template>'
`<xsl:output method="formato_salida"/>`
`<xsl:apply-templates/>`

###XPath: el lenguaje complementario
XPath es el lenguaje, también expresado en XML, que nos permite seleccionar y viajar a través del documento XML que estamos procesando. Hay otros lenguajes que utilizan XPath, como por ejemplo XQuery. 
En el programa oXygen hay un recuadro que nos permite interrogar nuestro texto con XPath. Ejecutad los siguientes comandos: 
- `/TEI`
- `/TEI/teiHeader/fileDesc/titleStmt/title`
- `//title`
- `/TEI/text/body/div[@xml:id='prologo']`
- `/TEI/text/body/div/head[@type='titulo']`
- `//persName`
- `//persName[@xml:id]`

### XPath ejes (axes)
self::<br/>
child::, descendant::<br/>
parent::, ancestor::<br/>
following::, following-sibling::<br/>
preceding::, preceding-sibling::<br/>
attribute::<br/>





###Resources:
- [Doug Tidwell. *XSLT*. O'Reilly, 2001](http://docstore.mik.ua/orelly/xml/xslt/index.htm)
- [M. Holmes. *An Introduction to XSLT for Digital Humanists*. DHOXSS 2013](http://web.uvic.ca/~mholmes/dhoxss2013/)
- [David J. Birnbaum. *The role of XSLT in digital libraries, editions...* 2013](http://malta.obdurodon.org/)
- [W3Schools. XSLT Tutorial.](http://www.w3schools.com/xsl/default.asp)
- [Julia Flanders and Syd Bauman. *A Gentle Introduction to XSLT.* 2013](http://www.wwp.northeastern.edu/outreach/seminars/publishing_2013-11/presentations/xslt_intro/xslt_intro_00.xhtml)
- [Laura Mandell, Brian Pytlik-Zillig, Syd Bauman, and others. *XSLT for Humanistis*](http://idhmc.tamu.edu/chat/xslt/customize2.html#body.1_div.1)