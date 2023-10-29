# Big Red Bigraph Model

Big Red is a graphical development environment for bigraphs published in [[1]](#References).
Refer also to the original repository: [http://github.com/ale-f/big-red](http://github.com/ale-f/big-red).

This project is an extract of the Java package [`org.bigraph.model`](https://github.com/ale-f/big-red/tree/master/plugins/org.bigraph.model) of Big Red, which encompasses the classes that constitute Big Red's view on the bigraph model.
Thus, this project provides access to essential functions on the model in external tools, for instance, to implement converters, without
using the complete Eclipse environment.

No changes are made to the original Java package, which is released under the same conditions.

## Getting Started

### Maven Configuration

This artifact is deployed to the Central Repository.

```xml
<dependency>
    <groupId>org.bigraphs.model</groupId>
    <artifactId>bigred-core</artifactId>
    <version>1.0.0.20130228-1</version>
</dependency>
```

## License

This project is licensed under the Eclipse Public License - v 2.0 - see the [LICENSE](LICENSE) file for details.

## References

- [1] Faithfull, Alexander John; Perrone, Gian; Hildebrandt, Thomas T. (2013-06-25). "Big Red: A Development Environment for Bigraphs". Electronic Communications of the EASST: Volume 61: Graph Computation Models 2012.
