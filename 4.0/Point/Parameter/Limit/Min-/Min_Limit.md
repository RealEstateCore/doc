[Index](../../../../index.md) > [Point](../../../Point.md) > [Parameter](../../Parameter.md) > [Limit](../Limit.md) > [Min_Limit](#)
# Min_Limit

A parameter that places a lower bound on the range of permitted values of a Setpoint.


**Display name:** Min Limit<br />
**DTMI:** dtmi:org:brickschema:schema:Brick:Min_Limit;1

---

## Child interfaces
* [Min_Air_Flow_Setpoint_Limit](Min_Air_Flow_Setpoint_Limit/Min_Air_Flow_Setpoint_Limit.md)
* [Min_Chilled_Water_Differential_Pressure_Setpoint_Limit](Min_Chilled_Water_Differential_Pressure_Setpoint_Limit.md)
* [Min_Discharge_Air_Static_Pressure_Setpoint_Limit](../Static_Pressure_Setpoint-/Min-/Min_Discharge_Air_Static_Pressure_Setpoint_Limit.md)
* [Min_Fresh_Air_Setpoint_Limit](Min_Fresh_Air_Setpoint_Limit.md)
* [Min_Hot_Water_Differential_Pressure_Setpoint_Limit](Min_Hot_Water_Differential_Pressure_Setpoint_Limit.md)
* [Min_Position_Setpoint_Limit](../Position-/Min_Position_Setpoint_Limit.md)
* [Min_Speed_Setpoint_Limit](../Speed_Setpoint-/Min-.md)
* [Min_Static_Pressure_Setpoint_Limit](../Static_Pressure_Setpoint-/Min-/Min_Static_Pressure_Setpoint_Limit.md)
* [Min_Supply_Air_Static_Pressure_Setpoint_Limit](../Static_Pressure_Setpoint-/Min-/Min_Supply_Air_Static_Pressure_Setpoint_Limit.md)
* [Min_Temperature_Setpoint_Limit](Min_Temperature_Setpoint_Limit/Min_Temperature_Setpoint_Limit.md)

---

## Relationships

### Inherited Relationships
* **[Point](../../../Point.md):** isPointOf

---

## Properties

### Inherited Properties
* **[Parameter](../../Parameter.md):** lastKnownValue
* **[Point](../../../Point.md):** aggregate, customProperties, customTags, hasQuantity, hasSubstance, identifiers, name

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
