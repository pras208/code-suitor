# Shops Near You API

To add a new shop
```
Resource			: /shop
Description			: Adds a shop. The API would find out the latitude and longitude of the 
					  shop address using Google Maps API and store it with the address.
Method				: POST
Request Content-type: application/json
Example Request		:	{
						  "shopName": "Shop1",
						  "shopAddress": {
						    "number": "1",
						    "addressLine1" : "Sector 31",
						    "addressLine2" : "Gurgaon",
						    "postCode": "122001"
						  }
						}
Success Response	: 200 OK