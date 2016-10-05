# TravelHubApi Postman Collection

### Usage

1. Import [this](https://raw.githubusercontent.com/travelhubapi/postman-collection/master/collection.json) collection to postman
2. Choose your enviroment in postman and add the variables:
  - thub_client_id
  - thub_client_secret
  - thub_hotel_vendor_id

3. Call relative enviroment endpoint (Ex. **1 - enviroments/homol**) to populate the others enviroment variables
4. Call **2 - oAuth/Generate Token** endpoint to populate token enviroment variable with generated token
5. DONE! Now you can call any other endpoint that need token header

