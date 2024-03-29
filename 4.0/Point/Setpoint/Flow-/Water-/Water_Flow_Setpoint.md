[Index](../../../../index.md) > [Point](../../../Point.md) > [Setpoint](../../Setpoint.md) > [Flow_Setpoint](../Flow_Setpoint.md) > [Water_Flow_Setpoint](#)
# Water_Flow_Setpoint

Sets the target flow rate of water


**Display name:** Water Flow Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Water_Flow_Setpoint;1

---

## Child interfaces
* [Bypass_Water_Flow_Setpoint](Bypass-.md)
* [Chilled_Water_Flow_Setpoint](Chilled-/Chilled_Water_Flow_Setpoint.md)
* [Condenser_Water_Flow_Setpoint](Condenser-.md)
* [Entering_Water_Flow_Setpoint](Entering-/Entering_Water_Flow_Setpoint.md)
* [Hot_Water_Flow_Setpoint](Hot-/Hot_Water_Flow_Setpoint.md)
* [Leaving_Water_Flow_Setpoint](Leaving-/Leaving_Water_Flow_Setpoint.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Point](../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Setpoint](../../Setpoint.md):** lastKnownValue

---

## Target Of
### General
* [Point](../../../Point.md).isPointOf
* [Agent](../../../../Agent/Agent.md).owns
* [Space](../../../../Space/Space.md).isLocationOf
* [Equipment](../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../Information/Document/Document.md).url
* [Lease](../../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../Information/ServiceObject/ServiceObject.md).producedBy
