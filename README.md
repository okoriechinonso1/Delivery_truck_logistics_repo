This project is a truck delivery logistics project.

Description of the Dataset:
GpsProvider - Vendor who provides GPS
BookingID - Unique Identification for a trip
Market/Regular - Type of trip. Regular - Vendors with whom we will have contract. Market - Vendor with whom we will not have contract
BookingIDDate - Date when booking was created vehicleno - Truck Number
OriginLocation - Trip start place DestinationLocation - Trip end place
Orglatlon - Latitude/Longitude of start place
Deslatlon - Latitude/Longitude of end place
DataPingtime - Time when we receive GPS ping
PlannedETA - Planned Estimated Time of Arrival CurrentLocation - Live location
DestinationLocation - Repeat of destination location
actualeta - Time when the truck arrived Currlat - current latitude - changes each time when we receive GPS ping
Currlon - current longitude - changes each time when we receive GPS ping ontime - If the truck arrived on time - calculated based on Planned and Actual ETA delay - If the truck arrived with a delay - calculated based on Planned and Actual ETA OriginLocationCode - Origin code
DestinationLocationCode - Destination code tripstartdate - Date/Time when trip started tripenddate Date/Time when trip ended - based on documentation (cant be considered for calculating delay)\ TRANSPORTATIONDISTANCEINKM - Total KM of travel
vehicleType - Type of Truck
Minimumkmstobecoveredinaday - Minimum KM the driver needs to cover in a day DriverName - Driver details
Driver_MobileNo - Driver details
customerID - Customer details
customerNameCode - Customer details
supplierID - Supplier - Who provides the vehicle
supplierNameCode - Supplier - Who provides the vehicle