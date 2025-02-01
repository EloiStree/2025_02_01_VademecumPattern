```
THIS PACKAGE IS A REMINDER OF SOMETHING I NEED AND WANT TO CODE.
IT IS NOT IMPLEMENTED YET.
```
-------------

# 2025_02_01_VademecumPattern

I learned about a thinking pattern in the past called "Vademecum." Now, I would like to implement it in Unity3D as code, rather than using a node-based system.

🤖 "Vademecum" is a Latin term meaning "go with me." It typically refers to a handbook or reference guide that is meant to be carried around and consulted frequently. However, the coding pattern you're describing seems closer to a functional programming paradigm—where an input always produces the same output without side effects. Another related concept is a "pipeline" or a "transformer function," which processes input data and returns a result.

I like the idea of Shader Graph blocks, where each block processes data and provides an output. This concept allows for isolated, modular code—similar to Blueprints—operating on primitive data types.

However, I’m hesitant about using UI-based node systems, as they are primarily designed for 2D interfaces, while I need something that works in a real-time 3D XR environment.

With that in mind, this package is an attempt to explore a "Vademecum Pattern" in Unity.

Data is processed using structured input and output, exclusively through structs.
Logic is cleanly separated and executed efficiently using the Job System.
This approach should ensure modular, scalable, and high-performance code without relying on visual scripting.
