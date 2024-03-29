[Index](../../../../../index.md) > [Point](../../../../Point.md) > [Setpoint](../../../Setpoint.md) > [Temperature_Setpoint](../../Temperature_Setpoint.md) > [Air_Temperature_Setpoint](../Air_Temperature_Setpoint.md) > [Unoccupied_Air_Temperature_Setpoint](#)
# Unoccupied_Air_Temperature_Setpoint

Sets temperature of air when unoccupied


**Display name:** Unoccupied Air Temperature Setpoint<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Unoccupied_Air_Temperature_Setpoint;1

---

## Child interfaces
* [Unoccupied_Air_Temperature_Cooling_Setpoint](Unoccupied_Air_Temperature_Cooling_Setpoint.md)
* [Unoccupied_Air_Temperature_Heating_Setpoint](Unoccupied_Air_Temperature_Heating_Setpoint.md)
* [Unoccupied_Discharge_Air_Temperature_Setpoint](Unoccupied_Discharge_Air_Temperature_Setpoint.md)
* [Unoccupied_Return_Air_Temperature_Setpoint](Unoccupied_Return_Air_Temperature_Setpoint.md)
* [Unoccupied_Room_Air_Temperature_Setpoint](Unoccupied_Room_Air_Temperature_Setpoint.md)
* [Unoccupied_Supply_Air_Temperature_Setpoint](Unoccupied_Supply_Air_Temperature_Setpoint.md)
* [Unoccupied_Zone_Air_Temperature_Setpoint](../Zone-/Unoccupied-.md)

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
