[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Setpoint](../../../Setpoint.md) > [Flow_Setpoint](../../Flow_Setpoint.md) > [Air_Flow_Setpoint](../Air_Flow_Setpoint.md) > [Discharge_Air_Flow_Setpoint](#)
# Discharge_Air_Flow_Setpoint

Sets discharge air flow


**Display name:** Discharge Air Flow Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Discharge_Air_Flow_Setpoint;1

---

## Child interfaces
* [Cooling_Discharge_Air_Flow_Setpoint](Cooling-/Cooling_Discharge_Air_Flow_Setpoint.md)
* [Discharge_Air_Flow_Demand_Setpoint](Discharge_Air_Flow_Demand_Setpoint.md)
* [Heating_Discharge_Air_Flow_Setpoint](Heating-/Heating_Discharge_Air_Flow_Setpoint.md)
* [Occupied_Discharge_Air_Flow_Setpoint](Occupied-/Occupied_Discharge_Air_Flow_Setpoint.md)
* [Unoccupied_Discharge_Air_Flow_Setpoint](Unoccupied-/Unoccupied_Discharge_Air_Flow_Setpoint.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Point](../../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name
* **[Setpoint](../../../Setpoint.md):** lastKnownValue

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
