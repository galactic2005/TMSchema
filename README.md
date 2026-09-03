# Total Miner XML Schema

A XML Schema file made for Total Miner. Works for both vanilla and modded elements.

## Modded

Currently the Schema has support for the following modded elements:

* `ArrayOfItemXML`
* `ArrayOfModActorAIDataXML`
* `ArrayOfModActorPhysicsDataXML`
* `ArrayOfModActorTypeDataXML`
* `ArrayOfModDeathMessageXML`
* `ArrayOfModSpawnRuleXML`

## Vanilla

Currently the Schema has support for the following vanilla elements:

* `ArrayOfActorAIDataXML`
* `ArrayOfActorPhysicsDataXML`
* `ArrayOfDeathMessageXML`
* `ArrayOfPlaylistXML`
* `ArrayOfSpawnRuleXML`

## Implementation

When making your XML file, do this to reference the Schema:

```xml
<?xml version="1.0"?>
<?xml-model href="https://raw.githubusercontent.com/galactic2005/TMSchema/refs/heads/main/TMSchema.xsd" type="application/xml" schematypens="http://www.w3.org/2001/XMLSchema"?>

<Example xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">

<Example/>
```
