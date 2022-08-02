Entity: ConsumptionPoint
========================
  

[Open License](Link to licence.md file)  

[document generated automatically]()  

Global description: **This entity contains a harmonised description of a Consumption Point and its cost**  


## List of properties  
- `id`: Unique identifier of the entity.
- `category`: Category of the consumption point. Enum: ...
- `name`: The name of this item.
- `alternateName`: An alternative name for this item.
- `address`:  The mailing address.
- `addressCountry`: Property. The country. For example, Spain.
- `addressLocality`: Property. The locality in which the street address is, and which is in the region. Model: https://schema.org/addressLocality.
- `code`: An identifier code for this item.
- `dateCreated`: Entity creation timestamp. This will usually be allocated by the storage platform.
- `dateModified`: Timestamp of the last modification of the entity. This will usually be allocated by the storage platform.
- `description`: A description of this item.
- `location`: Geojson reference to the item. It can be Point, LineString, Polygon, MultiPoint, MultiLineString or MultiPolygon.
- `type`: NGSI Entity type. It has to be ConsumptionPoint


Required properties 
- `id`
- `type`  

This entity is used in applications that use spatial data and is applicable to Automotive, Environment, Industry and Smart City vertical segments and related IoT applications. Created with contributions of ECOOO project.  

## Data Model description of properties