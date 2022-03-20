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

Cites:

* Algorithm: <http://www.mathe2.uni-bayreuth.de/axel/papers/reingold:graph_drawing_by_force_directed_placement.pdf>
* Python implementation of algorithm: <https://gist.github.com/mmisono/8972731>

## References

“d3-force” documentation <https://github.com/d3/d3-force/blob/main/README.md>
Kobourov, Stephen G. 2013. “Force-Directed Drawing Algorithms.” In Roberto Tamassia (editor), *Handbook of Graph Drawing and Visualization*, p. CRC Press, 2013, 383–408. <https://cs.brown.edu/people/rtamassi/gdhandbook/chapters/force-directed.pdf>
Mchedlidze, Tamara. 2016. “Algorithms for Graph Visualization Force-Directed Algorithms.” <https://i11www.iti.kit.edu/_media/teaching/winter2016/graphvis/graphvis-ws16-v6.pdf>
Roth, Tom. “Force graphs” <https://tomroth.com.au/d3/#force-graphs>
Wu, Shirley. 2014. “Understanding the force”. <https://medium.com/@sxywu/understanding-the-force-ef1237017d5>
