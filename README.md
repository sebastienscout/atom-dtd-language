# Language-dtd package for Atom

Adds syntax highlighting and snippets to DTD (Document Type Definition) files in Atom.

## Snippets

### From DTD file

| Snippets      | Result                                         |
| ------------- |:----------------------------------------------:|
| `<`           | &lt;!NAME element&gt;                          |
| `element`     | &lt;!ELEMENT name (content)&gt;                |
| `attlist`     | &lt;!ATTLIST element attribute TYPE #VALUE&gt; |
| `entity`      | &lt;!ENTITY name "value"&gt;                   |

### From XML file

| Snippets          | Result                                         |
| ----------------- |:----------------------------------------------:|
| `dtd-simple`      | &lt;!NAME element&gt;                          |
| `dtd-element`     | &lt;!ELEMENT name (content)&gt;                |
| `dtd-attlist`     | &lt;!ATTLIST element attribute TYPE #VALUE&gt; |
| `dtd-entity`      | &lt;!ENTITY name "value"&gt;                   |
| `dtd-local`       | Generates a local DTD environment              |
| `dtd-import`      | Import an external DTD file                    |

## Bugs

Feel free to report an issue and make a request.
