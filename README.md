# gascii-doc

## Overview

Documents with asciidoc, plantuml and swagger.

```
src/
  - docs/
    - asciidoc/
      - swagger/    # generated from swagger yml
      - pu/
        - *.pu      # plantuml diagrams
      - *.adoc      # asciidocs
  - swagger/
    - api.yml       # api definition
```

## Usage
```
$ ./gradlew

$ ls -l build/docs/{html5,pdf}
```

## Requirements
- plantuml
- graphviz
- (gradle)

## Links
- asciidoc  
http://asciidoc.org/
- swagger.io  
https://swagger.io/
- plantuml  
http://plantuml.com/
