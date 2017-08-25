# SOLID PENIS
The best iOS design principles

SOLID PENIS commonly used with [PIDOR](https://github.com/ApplePride/PIDOR)

## Overview
* [Single responsibility principle](#single-responsibility-principle)
* [Open/closed principle](#open-closed-principle)
* [Liskov substitution principle](#the-liskov-substitution-principle)
* [Interface segregation principle](#the-interface-segregation-principle)
* [Dependency inversion principle](#the-dependency-inversion-principle)



* [Polymorphism](#polymorphism)
* [Encapsulation](#encapsulation)
* [Nested avoidance principle](#nested-avoidance-principle)
* [Inheritance plane](#inheritance-plane)
* [Style guide compliance](#style-guide-compliance)

## Description
### Single responsibility principle
THERE SHOULD NEVER BE MORE THAN ONE REASON FOR A CLASS TO CHANGE
### Open closed principle
SOFTWARE ENTITIES (CLASSES, MODULES, FUNCTIONS, ETC.) SHOULD BE OPEN FOR EXTENSION, BUT CLOSED FOR MODIFICATION.
### The Liskov Substitution Principle
FUNCTIONS THAT USE POINTERS OR REFERENCES TO BASE CLASSES MUST BE ABLE TO USE OBJECTS OF DERIVED CLASSES WITHOUT KNOWING IT.
### The Interface Segregation Principle
CLIENTS SHOULD NOT BE FORCED TO DEPEND UPON INTERFACES THAT THEY DO NOT USE.
### The Dependency Inversion Principle
A. HIGH LEVEL MODULES SHOULD NOT DEPEND UPON LOW LEVEL MODULES. BOTH SHOULD DEPEND UPON ABSTRACTIONS.
B. ABSTRACTIONS SHOULD NOT DEPEND UPON DETAILS. DETAILS SHOULD DEPEND UPON ABSTRACTIONS.
### Polymorphism
A VARIABLE THAT MAY REFER TO OBJECTS WHOSE CLASS IS NOT KNOWN AT COMPILE TIME AND WHICH RESPOND AT RUN TIME ACCORDING TO THE ACTUAL CLASS OF THE OBJECT TO WHICH THEY REFER.
### Encapsulation
YOU SHOULD PROVIDE WELL-DEFINED INTERFACE TO A SET OF FUNCTIONS IN A WAY WHICH HIDES THEIR INTERNAL WORKINGS.
### Nested avoidance principle
```swift 
if {
  if {
    if {
     if {
      //and so on
     }
    }
  }
}
```
- THIS CODE IS HARD TO READ
- CONTEXT IS HARD TO UNDERSTAND
- PEOPLE HATE YOU...
### Inheritance plane
INHERITANCE IN WIDTH IS MORE PREFERABLE THAN IN DEPTH
### Style guide compliance
[FIND OUT](https://github.com/raywenderlich/swift-style-guide)
