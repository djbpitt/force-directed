## Winona Salesky

(<https://xmlcom.slack.com/archives/C011NLXE4DU/p1647612439594299?thread_ts=1647611838.844509&cid=C011NLXE4DU>)

* <https://anthology.lib.virginia.edu/lod.html?view=graph&type=force&data=all>
* <https://usaybia.net/person/1>
* <http://poetess.dh.tamu.edu/index.html>
* <https://medievalmideast.org/person/7442.html>

These are generated via XSLT or XQuery, run on the TEI files to extract JSON for the d3js visualization. 
All the code is on github, and I’m happy to answer any questions you might have about it.

## Martynas Jusevicius

<https://github.com/AtomGraph/Web-Client/blob/master/src/main/webapp/static/com/atomgraph/client/xsl/converters/RDFXML2SVG.xsl>


We're rendering RDF graphs as force-directed SVG layout.
The Saxon-JS layer only adds interactivity.
The layout logic is in a plain XSLT 3.0 stylesheet.
It transforms normalized (by Jena) RDF/XML output.
