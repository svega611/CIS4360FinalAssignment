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
    - Inputs:
      -  flight_id
    - Responses:
      -  Success/Error
    - Expected Result:
      - Money is refunded to all customer_id on flight_id