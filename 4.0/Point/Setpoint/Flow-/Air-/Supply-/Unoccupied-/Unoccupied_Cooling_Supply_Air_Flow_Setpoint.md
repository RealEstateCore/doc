[Index](../../../../../../index.md) > [Point](../../../../../Point.md) > [Setpoint](../../../../Setpoint.md) > [Flow_Setpoint](../../../Flow_Setpoint.md) > [Air_Flow_Setpoint](../../Air_Flow_Setpoint.md) > [Supply_Air_Flow_Setpoint](../Supply_Air_Flow_Setpoint.md) > [Unoccupied_Supply_Air_Flow_Setpoint](Unoccupied_Supply_Air_Flow_Setpoint.md) > [Unoccupied_Cooling_Supply_Air_Flow_Setpoint](#)
# Unoccupied_Cooling_Supply_Air_Flow_Setpoint

**Display name:** Unoccupied Cooling Supply Air Flow Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Unoccupied_Cooling_Supply_Air_Flow_Setpoint;1

---

## Relationships

### Inherited Relationships
* **[Point](../../../../../Point.md):** isPointOf

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|tags|**en**: Tags|**en**: Brick tags associated with this interface.|map (string->boolean)|False|
### Inherited Properties
* **[Point](../../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Setpoint](../../../../Setpoint.md):** lastKnownValue

---

## Target Of
### General
* [Point](../../../../../Point.md).isPointOf
* [Agent](../../../../../../Agent/Agent.md).owns
* [Space](../../../../../../Space/Space.md).isLocationOf
* [Equipment](../../../../../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../../../../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../../../../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../../../../../Information/Document/Document.md).documentTopic
* [Document](../../../../../../Information/Document/Document.md).url
* [Lease](../../../../../../Event/Lease.md).leaseOf
* [PointOfInterest](../../../../../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../../../../../Collection/Portfolio.md).includes
* [ServiceObject](../../../../../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../../../../../Asset/Equipment/Meter/Meter.md).meters
### Inherited
* [ActuationEvent](../../../../../../Event/Point-/ActuationEvent.md).targetPoint
* [Architecture](../../../../../../Space/Architecture/Architecture.md).hasPoint
* [Asset](../../../../../../Asset/Asset.md).hasPoint
* [ExceptionEvent](../../../../../../Event/Point-/ExceptionEvent.md).sourcePoint
* [ObservationEvent](../../../../../../Event/Point-/ObservationEvent/ObservationEvent.md).sourcePoint
* [ServiceObject](../../../../../../Information/ServiceObject/ServiceObject.md).producedBy
