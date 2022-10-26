# Http Server

## Device
* name
* model
* isActive
* ports

## Port
* name
* type

## Cables
* name
* deviceA
* deviceZ
* length

## Remote API approach
* GET /getAllDevices -  JSP OK
* GET /addNewDevice - HTML OK - form add new device
* POST /addNewDevice - HTML OK - process form

## REST
* GET /devices - get all devices from DB
* GET /devices/{id} - get device by id

* — GET /devices/{id}/ports
* — GET /devices/{device_id}/ports/{port_id}

* POST /devices - create new device
* POST /devices/{id}/ports

* // PUT /devices/{id} - update existing device
* // PATCH /devices/{id} - update existing device
* DELETE /devices/{id} - remove device from db

* GET /devices/{id}/ports
* POST /devices/{id}/ports