[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Parameter](../../../Parameter.md) > [PID_Parameter](../../PID_Parameter.md) > [Proportional_Band_Parameter](../Proportional_Band_Parameter.md) > [Differential_Pressure_Proportional_Band](#)
# Differential_Pressure_Proportional_Band

**Display name:** Differential Pressure Proportional Band<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Differential_Pressure_Proportional_Band;1

---

## Child interfaces
* [Chilled_Water_Differential_Pressure_Proportional_Band_Parameter](Chilled_Water-_Parameter.md)
* [Entering_Water_Differential_Pressure_Proportional_Band_Parameter](Entering_Water-_Parameter.md)
* [Hot_Water_Differential_Pressure_Proportional_Band_Parameter](Hot_Water-_Parameter.md)
* [Leaving_Water_Differential_Pressure_Proportional_Band_Parameter](Leaving_Water-_Parameter.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Parameter](../../../Parameter.md):** lastKnownValue
* **[Point](../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name

---

## Target Of
### General
* [Point](../../../../Point.md).isPointOf
* [Agent](../../../../../Agent/Agent.md).owns
* [Space](../../../../../Space/Space.md).isLocationOf
* [Equipment](../../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../../Information/Document/Document.md).url
* [Lease](../../../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../Information/ServiceObject/ServiceObject.md).producedBy
