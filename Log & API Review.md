## Log & API Review

Postman tests and application logs revealed:

- API timeouts occurred before Ikeja Electric returned confirmation

- The system marked transactions as failed after timeout thresholds

- Late confirmations from the biller were not consistently reconciled

This created scenarios where:

- Customer debit succeeded

- Bill payment confirmation arrived late

- System recorded the transaction as failed or pending
