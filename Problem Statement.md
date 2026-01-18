### Problem Statement

- Customers attempting to pay Ikeja Electric bills experienced:

- Transactions returning failed or pending statuses on the app/USSD

- Delayed or missing confirmation despite successful debit

- Increased complaints and support escalations

- Manual reversals in some edge cases

Operational dashboards showed:

- Elevated failure rates for IKEDC compared to other electricity billers

- Spike in null or timeout-related responses during peak hours

### Initial Observations

- Failures were not consistent; some transactions succeeded under identical conditions

- Other billers on the same switch showed lower failure rates

- Most failures occurred during high transaction volume windows

This suggested a partner-specific or integration-specific issue, rather than a core platform outage.
