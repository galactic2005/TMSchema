# Total Miner XML Schema

A XML Schema file made for Total Miner. Works for both vanilla and modded elements.

## Implementation

When making your XML file, do this to reference the Schema:

```xml
<?xml version="1.0"?>
<?xml-model href="https://raw.githubusercontent.com/galactic2005/TMSchema/refs/heads/main/TMSchema.xsd" type="application/xml" schematypens="http://www.w3.org/2001/XMLSchema"?>

<Example xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">

<Example/>
```

### Modded Elements

Currently the Schema has support for the following modded elements:

#### Modded Actors

* `ArrayOfModActorAIDataXML`
* `ArrayOfModActorAudioDataXML`
* `ArrayOfModActorBoundsDataXML`
* `ArrayOfModActorLevelDataXML`
* `ArrayOfModActorPhysicsDataXML`
* `ArrayOfModActorTypeDataXML`
* `ArrayOfModSpawnRuleXML`

#### Modded Items

* `ArrayOfItemXML`
* `ArrayOfModItemCombatDataXML`
* `ArrayOfModItemRarityDataXML`
* `ArrayOfModItemTypeClassDataXML`

#### Other Modded XMLs

* `ArrayOfModDeathMessageXML`

### Vanilla Elements

Currently the Schema has support for the following vanilla elements:

#### Vanilla Actors

* `ArrayOfActorAIDataXML`
* `ArrayOfActorAudioDataXML`
* `ArrayOfActorLevelDataXML`
* `ArrayOfActorPhysicsDataXML`
* `ArrayOfActorTypeDataXML`
* `ArrayOfSpawnRuleXML`

#### Vanilla Items

* `ArrayOfItemCombatDataXML`
* `ArrayOfItemTypeClassDataXML`

#### Other Vanilla XMLs

* `ArrayOfAmbientSoundXML`
* `ArrayOfDeathMessageXML`
* `ArrayOfPlaylistXML`
