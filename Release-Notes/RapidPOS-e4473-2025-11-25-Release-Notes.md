# Rapid POS e4473 Integration Release Notes  

*Release Date: November 25, 2025*

---

## What's New

### e4473 Cashier Portal:

- Added validation to raise error if Driver's License Expiration is left blank on Section C. 
- Resolved issue where selecting Delay and Additional Delay in Section C prevented termination of e4473.       

### e4473 Customer App:

- Updated verbiage from “Submit” to “Insert Today's Date and Submit”  
- Updated Middle Name character limit from 15 to 50. Counterpoint accepts up to a 50 character middle name. However, if the first + middle + last name exceed 40 characters, it will truncate the middle name.

### 4473Cloud Integration:
- Added functionality to always send a Status Date for all 4473's, including Terminated 4473's. 
