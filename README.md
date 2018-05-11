# Roster prefill
* Use the household members roster to prefill the fertility roster
# State lookup
* Use the state id to look up the state name
# Launch application
* Use a menu application to launch a survey application with prefilled data
## Tips for creating a menu application
* Don't add MENU_ID to form 
* Menu PFF configurations
    * Add ```Description=Launch Application```, so descriptive name is displayed on mobile Entry Application screen
    * Add ```StartMode=Add```, so Case Listing screen is bypassed. This behavior is necessary to allow ```Lock=Caselisting``` to disable the Case Listing screen.
    * Add ```Lock=CaseListing```, so Case Listing screen is disabled
* Data entry options
    * Turn off "Show case tree" since the case tree is not useful in a menu
    * Turn on "Automatically advance on selection," so interviewers do not have to tap next

