# Python-pyGexf
Modified Version of package pyGexf for Python 3.x

Fixed Indent and Spaces Error, together with the exception handler to make it run under Python 3.x in PyCharm

# Usage

  gexf = Gexf("Paul Girard","A hello world! file")<br>
  graph=gexf.addGraph("directed","static","a hello world graph")<br>

  graph.addNode("`node`","`label`")<br>
  graph.addNode("`node`","`label`")<br>
  graph.addEdge("`label`","`node`","`node`")<br>

  output_file = open("Output.gexf", "wb+") # Notice that it have to be `wb+` to be writable<br>
  gexf.write(output_file)<br>
