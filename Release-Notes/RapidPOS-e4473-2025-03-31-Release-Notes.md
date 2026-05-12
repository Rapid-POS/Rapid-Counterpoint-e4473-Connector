# Rapid POS e4473 Integration Release Notes  

*Release Date: March 31, 2025*

---

## What's New

### e4473 and Counterpoint:

-	Update to Counterpoint to assign e4473 based on CP Location (previously assigned to CP Store). Will allow for ecommerce orders to be picked up from multiple retail store locations.  

### e4473 Cashier Portal:

-	Counterpoint: For Multiple Line Type tickets, send to e4473 only Firearms that are on CP Sale lines when Ticket is put on Hold. If Firearms are Layaway/Order lines, create e4473 when Layaway/Order is saved. 
- 4473 Termination: Add Terminate Reason for "Buyer/Seller Cancelled Purchase"
- 4473 Termination: Show Terminate Reason on e4473
- Section C: When 27d (No response was provided within 10 business days after additional delay…) is checked, update e4473 Status to allow for disposition
- Section C: Auto-Populate Q24 with ATF Type from Counterpoint Item
- Section C: Allow answers to 27, 28 and 29 on the same e4473
- Section D: After e4473 Recertification, update e4473 Status to the one indicated in Section C
- Section D: Update Verbiage on e4473 Section D error  
- Section E: Updated 30 day validation between Section B and Section E signatures to raise a message
- Section E: Validate Transfer Date on Section E is not later than today. 
- Section E: Add error message on Section E when not signed
- Section E: Disallow Changes to the e4473 after Section E is signed. Disallow Firearm & S/N Changes to the CP Ticket after Section E is signed. 
- Section E: Raise message on Section E to confirm Firearms on Section A before signing. 
