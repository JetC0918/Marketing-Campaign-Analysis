## Data Description
Attached you will find three files with the data you will need to complete the analysis.

**`client_data.csv`: You will find data specific to fictional clients**

- `client_id`: Randomly generated unique surrogate identifier for a client
- `client_geographical_region`: Client geographical location in relation to U.S. Census definitions
- `client_residence_status`: Client residence status in relation to whether they rent or own
- `client_age`: Client age in relation to date of birth
- `deposit_data.csv`: You will find data specific to the client deposit behavior

**`client_id`: Randomly generated unique surrogate identifier for a client**

- `deposit_type`: Delineates whether a client deposit is the scheduled record or actual record
- `deposit_amount`: Client deposit amount to the dedicated bank account with Freedom
- `deposit_cadence`: Timing and pattern of client deposit activity
- `deposit_date:` Deposit date for deposit type

**`calendar_data.csv`: This is a calendar reference table**

- `gregorian_date`: This date aligns with the Gregorian calendar
- `month_name:` These are the designated months in the case study
    - Month 1 and 2 are pre-campaign
    - Month 3 is the campaign
    - Month 4 and 5 are post-campaign