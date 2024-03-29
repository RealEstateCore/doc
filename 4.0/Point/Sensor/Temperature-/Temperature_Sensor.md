[Index](../../../index.md) > [Point](../../Point.md) > [Sensor](../Sensor.md) > [Temperature_Sensor](#)
# Temperature_Sensor

Measures temperature: the physical property of matter that quantitatively expresses the common notions of hot and cold


**Display name:** Temperature Sensor<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Temperature_Sensor;1

---

## Child interfaces
* [Air_Temperature_Sensor](Air-/Air_Temperature_Sensor.md)
* [Air_Wet_Bulb_Temperature_Sensor](Air-/Air_Wet_Bulb_Temperature_Sensor/Air_Wet_Bulb_Temperature_Sensor.md)
* [Heat_Sink_Temperature_Sensor](Heat_Sink-.md)
* [Natural_Gas_Temperature_Sensor](Natural_Gas-.md)
* [Radiant_Panel_Temperature_Sensor](Radiant_Panel-/Radiant_Panel_Temperature_Sensor.md)
* [Soil_Temperature_Sensor](Soil-.md)
* [Water_Temperature_Sensor](Water-/Water_Temperature_Sensor.md)

---

## Components

|Name|Display name|Description|Schema|
|-|-|-|-|
|lastKnownValue|**en**: last known value||[TemperatureObservation](../../../Event/Point-/ObservationEvent/TemperatureObservation.md)|

---

## Relationships

### Inherited Relationships
* **[Point](../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Point](../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name

---

## Target Of
### General
* [Point](../../Point.md).isPointOf
* [Agent](../../../Agent/Agent.md).owns
* [Space](../../../Space/Space.md).isLocationOf
* [Equipment](../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../Information/Document/Document.md).documentTopic
* [Document](../../../Information/Document/Document.md).url
* [Lease](../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../Information/ServiceObject/ServiceObject.md).producedBy
