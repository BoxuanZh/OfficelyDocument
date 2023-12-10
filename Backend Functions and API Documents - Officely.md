##  Backend Functions and API Documents - Officely

 

* Authentication & Authorization
* Database Definition 
* User application API
* Admin web API
* API For other group (do we need this?)



### For User 

------------------------

1. Search

   * Description:

      Application sends request with filters, where **city** and **timeslot** fields are necessary. Server will response a list of available offices.

   * URL: */SearchOffice

   * method: POST

   * type: Json

   * Request : 

     ````
     {
         "city": "warsaw",
         "timeslot": {
             "start": "01/12/2023",
             "end": "30/12/2023"
         },
         "enableAdvancedFilter": true,
         "filters": {
             "name": "",
             "location": {
                 "x": 123.1,
                 "y": 52.2,
                 "limit": 5
             },
             "wifi": true,
             "price": {
                 "lower": 500,
                 "upper": 1000
             },
           	""
             // TODO: determine more filters
         }
     }
     ````

   * Response

     ````json
     ````

     

2. Check Availability

3. Book

4. Cancel

5. Profile Viewing

6. Profile Editing



### For Admin

-------------------



### Database Definition 

-----------------------





