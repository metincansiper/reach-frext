## Fries Output Converter and Reach Results Loader

This is a public code repository of the Computational Language Understanding (CLU) Lab led by [Mihai Surdeanu](http://surdeanu.info/mihai/) at [University of Arizona](http://www.arizona.edu).

Author: [Tom Hicks](https://github.com/hickst)

Purpose: Converts triples of FRIES-format JSON files, containing Reach results, into a simpler
format for ingestion into a Biopax program.

## Installation

This software requires Java 1.8, Gradle 2.7, and Groovy 2.4.x+.

To build the standalone JAR file in the build/libs subdirectory:

```
   > gradle clean shadowJar
```

To run the JAR file:

```
   > java -jar frext-2.7.0.jar -v /input/dir/path
```

Run Options:

```
Usage: frext [-h] [-v] directory
 -h,--help            Show usage information
 -v,--verbose         Run in verbose mode (default: non-verbose)
```

## License

Licensed under Apache License Version 2.0.

(c) The University of Arizona, 2017
