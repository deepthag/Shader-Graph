# Shader-Graph
MTEC-340 Unity Techniques Presentation

## Overview 

Shader Graph is a tool that allows you to build textures and materials visually rather than by writing code. The interface is another window within Unity and operates a lot like Max--you can create textures by connecting nodes together. 

## Tutorial

1. Create a Shader Graph asset. 
    (Create > Shader Graph > URP > select an option)
2. Double click to open Shader Graph window. 
3. Add nodes and connections as desired. 
    (Right click > Create Node > select an option)
    (drag from outlet to inlet to create connection)
4. Save the Shader Graph asset. 
5. Navigate to game object. Make sure a Mesh Renderer component is attached. 
6. Drag and drop Shader Graph asset into the "Materials" field of the Mesh Renderer. 
7. To make nodes of the Shader Graph editable in the Inspector window, convert the node to a property.
    (Right click on node > Convert To > Property)