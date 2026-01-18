## Failure Analysis
### Data Analysis

Using SQL queries and Power BI dashboards, transactions were analyzed by:

- Response codes

- Time of day

- Channel (USSD vs Mobile)

- API response times

Key findings:

- High occurrence of timeouts between Interswitch and Ikeja Electric

- Inconsistent response payloads during delayed responses

- Some transactions returned HTTP 200 but contained business-level failure or empty confirmation fields
