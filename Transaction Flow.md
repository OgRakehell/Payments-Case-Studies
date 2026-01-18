## Transaction Flow (Simplified)

1. Customer initiates IKEDC bill payment via Mobile App or USSD

2. Channel sends request to internal Payments API

3. Payments API forwards request to Interswitch

4. Interswitch routes request to Ikeja Electric

5. Response flows back through the same path

6. Customer receives success, failure, or pending notification
