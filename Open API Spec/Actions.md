1. Get Baggage Service Office Info
    - Method
      - GET
    - URL
      - /BaggageService/{airport_id}/info
    - Inputs: 
      - airport_id
    - Responses:
      - Location of baggage desk at airport_id
      - phone number for customer support
2. Refund for Canceled Flight
    - Method
      - PUT
    - URL
      /flight_service/{flight_id}/refund
    - Inputs:
      - flight_id
    - Responses:
      - Set customers refund flag to true on flight
    - Expected Result:
      - all customer_id on flight_id marked for refund 