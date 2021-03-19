[![Build Status](https://dev.azure.com/ixmeza/Web%20-%20Tests/_apis/build/status/ixmeza.postman.restfulbooker?branchName=master)](https://dev.azure.com/ixmeza/Web%20-%20Tests/_build/latest?definitionId=13&branchName=master)

# postman.restfulbooker

API tests for [restful booker](https://restful-booker.herokuapp.com/) using **postman**.

## Scenarios included

- Ping
- Auth
- Create booking
  * With valid data
  * With invalid data
- Update booking
  * With valid data 
  * With invalid data 
- Delete booking
  * Delete a booking
  * Delete all bookings

**NOTE: There are some:beetle:'s  in the API as it takes bad data such as: null values, checkin date later than checkout and negative prices & updating dates does not work correctly**


![Demo](/example.gif)
