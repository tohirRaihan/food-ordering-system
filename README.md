**depgraph-maven-plugin**

- A Maven plugin that generates dependency graphs in various formats (DOT, GML, PlantUML, JSON and Text)
- first install `graphviz`
- `mvn com.github.ferstl:depgraph-maven-plugin:aggregate -DcreateImage=true -DreduceEdges=false -Dscope=compile "-Dincludes=com.food.ordering.system*:*"`