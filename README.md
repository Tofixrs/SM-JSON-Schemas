# SM JSON Schemas

This repo is dedicated to housing json schemas of scrap mechanic json files  
For those who dont know json schemas are just documentation for jsons wich have all their properties and types documented

# How to use

1. Have a json language server
2. At the root of the json add a "$schema" property with the value of the url to the raw json file
   Like this

```json
{
  "$schema": "https://raw.githubusercontent.com/Tofixrs/SM-JSON-Schemas/0.6.6/shapeSet.json"
}
```

## TODO Descriptions:
Characters:
- ragdoll config
Harverstable:
- size description
RotationSet:
- 'prop' description
SubMesh:
- 'custom' & 'idx' description
ShapeSet:
- blockList: 'friction' & 'qualityLevel' description
- partList: 'density', 'characterShape', 'itemStack', 'carryItem', 'simpleInteractive', 'survivalSpring', 'restitution', 'harvestablePart', 'baseUuid', 'preview'
- where is `spotLight` used (capital L)
ToolList:
- idk if tool scripts can have `data`