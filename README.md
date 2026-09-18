Understanding Classes vs. Objects in Java

What is a Class?
A **class** is a conceptual blueprint, template, or design plan written by a software engineer. It defines the structure, attributes (what data it will hold), and behaviors (what actions it can perform) that an entity will have. By itself, a class is abstract and does not occupy space in the system's dynamic runtime memory (heap)—it simply dictates the rules for what data *will* look like once it is created.

What is an Object?
An **object** is a concrete, tangible instance created directly from a class blueprint. It is the physical reality of the design. When an object is instantiated using the `new` keyword, the system allocates real physical blocks of RAM memory to hold its specific state and values.

Conceptual Differences
* **Design vs. Reality:** A class is like the architectural blueprint of a house, while an object is the physical house built on the street. You cannot live inside a blueprint, and you cannot store data inside a raw class definition.
* **State vs. Structure:** A class defines *what properties* exist (e.g., brand, RAM size). An object holds the *actual values* for those properties (e.g., Dell, 16GB).
* **Memory Allocation:** A class exists statically as metadata in the permanent compiler space. An object occupies dynamic runtime space in the computer's heap memory.
* **One-to-Many Relationship:** You only write a class definition **once** in your source code files, but you can use it to create an **infinite** number of unique objects that operate independently of one another.
