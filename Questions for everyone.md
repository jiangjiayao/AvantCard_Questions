# AvantCard


For Jason

- [x] Why dont give decline page when declined, why rather say '24 hrs...' softer tone.
- [x] When asking for phone numbers, which type do we prefer? Can we put 'mobile' as default? working on it.
- [x] cards.avant.com not working? avant.com/card --> note: only for account management
- [x] When setting up auto-pay, option to save bank info? yes, even not enrolled in autopay.




From Stefan

- Initial credit assignment
  - APR assignment
  - Credit line assignment

- Verifications
  - SMS/phone verification required

- Management
  - Authorization
    - Overlimit
  - Credit line increase
  - Credit line decearse


For Stefan
- [x] Pricing strategy identifier: first digit is amf, last one is spread apr, second letter is for MLA
    - 0001 --> $00 fee, 17.74% spread
    - 0002 --> $00 fee, 20.74% spread
    - 2001 --> $29 fee, 17.74% spread
    - 2002 --> $29 fee, 20.74% spread
    - 3001 --> $39 fee, 17.74% spread
    - 2M01 --> $29 fee, 17.74% spread, with MLA status
    - 3M01 --> $39 fee, 17.74% spread, with MLA status
- [x] Do we have a way to identify emerging or established customers? --> Sql from Igor
- [x] On TU report, trade vs. open_trade vs. open_trade_satisfactory --> trade: open + closed, open_trade: accts still open, open_trade_satisfactory: accts still open and not delq
- [x] What is verified? e.g. Utilization for open revolving trades verified in past 12 months --> dont know
- [x] Rating on trades? e.g. Worst rating on credit card trades in past 12 months --> 30 day late, 60 day late, etc
- [x] Aggregate balance vs. Total balances? e.g. AT99 vs AT33 --> total: only for open ones
- [x] What is retail trade? --> private label
- [x] ${TABLE}.customer_id, which table is it referring to? --> referring to that view