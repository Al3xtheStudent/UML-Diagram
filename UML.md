#sample UML diagram for CSC102 by Alexzander Rodriguez <br>
#alerodr1@uat.edu

Create a diagram with 2 classes. Those classes need 3 attributes/ properties, 3 methods

```mermaid
    classDiagram
    class Shape{
        -length
        -width
        -height
        +getLength()
        +setLength()
        +getWidth()
        +setWidth()
    }

    class ShapeSig{
        -length : int
        -width : int
        -height : int
        +getLength() : int
        +setLength(n : int) : void
        +getWidth() : int
        +setWidth(n : int) : void
    }


```

Attributes come before properties or methods <br>
\+ public, \- private, \# protected <br>

```mermaid
    classDiagram
    class Superclass{
        
    }

    class Subclass1{
       
    }

    class Subclass2{
       
    }

    Superclass <|-- Subclass1
    Superclass <|-- Subclass2

```