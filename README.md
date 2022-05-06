# Reactjs-Onlineshopping-
// ADDRESS CONTROLLER 

GET METHOD:
-----------
http://localhost:9090/addressController/viewAllAddress
---------------------------------------------------------
OUTPUT:
-------
{
    {
        "addressId": "2",
        "streetNo": "400",
        "buildingName": "Supreme Building",
        "city": "Pune",
        "state": "Maharashtra",
        "country": "India",
        "pincode": "440010",
        "customer": null
    }
}
-----------------------------------------------------------
POST METHOD:
------------
http://localhost:9090/addressController/addAddress
------------------------------------------------------------
 
 {
        "addressId": "1",
        "streetNo": "420",
        "buildingName": "Supreme Apartment",
        "city": "Nagpur",
        "state": "Maharashtra",
        "country": "India",
        "pincode": "440018",
        "customer": {
            "customerId": "1",
            "firstName": "Sumit",
            "lastName": "Gangotri",
            "mobileNumber": "8149603242",
            "email": "sumit113@gmail.com"
        }
    }
------------------------------------------------------------------
    
PUT METHOD:
-----------
http://localhost:9090/addressController/updateAddress
--------------------------------------------------------------------
   {
        "addressId": "2",
        "streetNo": "400",
        "buildingName": "Supreme Building",
        "city": "Mumbai",
        "state": "Maharashtra",
        "country": "India",
        "pincode": "440010",
        "customer": {
            "customerId": "2",
            "firstName": "Sumit",
            "lastName": "Gour",
            "mobileNumber": "8149603242",
            "email": "sumit100@gmail.com"
        }
    }
-------------------------------------------------------------------------
GET METHOD:
-----------
http://localhost:9090/addressController/viewAddressBy/1
---------------------------------------------------------------------------
OUTPUT:
-------

{
    "addressId": "1",
    "streetNo": "420",
    "buildingName": "Supreme Apartment",
    "city": "Nagpur",
    "state": "Maharashtra",
    "country": "India",
    "pincode": "440018",
    "customer": {
        "customerId": "1",
        "firstName": "Sumit",
        "lastName": "Gangotri",
        "mobileNumber": "8149603242",
        "email": "sumit113@gmail.com"
    }
}
-----------------------------------------------------------------------------------

DELETE METHOD:
--------------
http://localhost:9090/addressController/removeAddress
--------------------------------------------------------------------------------------
