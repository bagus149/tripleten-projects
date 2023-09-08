## Project Description:
This project is about the packages offered by a company. There are two packages available: the Ultimate package and the Surf package. Each package has its own advantages according to the users' needs. The user data consists of 500 records collected in 2018. The goals of this project are as follows:
- Analyzing user behavior in choosing a package.
- Analyzing which package is the most profitable.
- Analyzing the revenue from the Ultimate and Surf packages.
- Analyzing the revenue from various cities.

## Data:

### Tabel *users*:
- *user_id* - users
- *firs_name* - user's first name
- *last_name* - user's last name
- *age* - user's age
- *reg_date* - Subscription start date
- *churn_date* - Date of service termination
- *city* - User's city of residence
- *plan* - The phone package name

### Tabel *calls*:
- *id* - The unique session ID for phone calls
- *call_date* - The call date
- *duration* - The call duration in minutes
- *user_id* - User ID who made the call

### Tabel *messages*:
- *id* - Unique SMS ID
- *message_date* - SMS sent date
- *user_id* - Unique user ID for sending SMS

### Tabel *internet*:
- *id* - Unique web session ID
- *mb_used* - The volume of data consumed during the session
- *session_date* - Session date for web usage
- *user_id* - User ID for web sessions

### Tabel *plans*:
- *plan_name* - Phone package name
- *usd_monthly_fee* - Monthly cost in US dollars
- *minutes_included* - Monthly allocation of call minutes
- *messages_included* - Monthly allocation of SMS
- *mb_per_month_included* - Monthly data volume allocation
- *usd_per_minute* - Price per minute if exceeded package limit
- *usd_per_message* - Price per SMS if exceeded package limit
- *usd_per_gb* - Price per extra gigabit if exceeded package limit

## Targets:
- Hypothesis test: The average income of Ultimate and Surf phone package users is different.
- Hypothesis test: The average income of users in the NY-NJ region is different from the income of users from other regions.
- 
## Libraries:
- *pandas*
- *numpy*
- *scipy*
- *matplotlib*
