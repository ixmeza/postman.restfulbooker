# postman.restfulbooker

API tests for [restful booker](https://restful-booker.herokuapp.com/) using **postman**.

## Scenarios included

- Ping
- Auth

<ul> Create booking
  <li> With valid data </li>
  <li> *With invalid data</li> 
</ul>
<ul> Update booking
  <li> With valid data </li>
  <li> *With invalid data</li> 
</ul>
<ul> Delete booking
  <li> Delete a booking </li>
  <li> Delete all bookings</li> 
</ul>

*There is a :beetle:  in the API as it takes bad data such as: null values, checkin date later than checkout and negative prices.
