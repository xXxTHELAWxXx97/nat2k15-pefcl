# nat2k15-pefcl
An integration script between the NAT2K15 framework and Project Error's PEFCL

# INITIAL RELEASE
## Version 1.0
This is the initial release of the integration script between Project Error's PEFCL and NAT2K15's money script. It uses a modified version of both scripts for the now and once pefcl has been updated to implement certain bug fixes the custom pefcl script will no longer be required. For the full list of PEFCL features check out their discord/website. 

### THINGS TO NOTE:
+ PEFCL will handle all banking balances from here on and the money script will only handle cash functions and hud display.
+ DO NOT try to update the bank balance with nats exports, you can still update the cash balance.
+ Bugs may still be present, please let me know either with a github issue. If your issue has not been addressed then feel free to reach out on discord and let me know its there.
+ If you are already using nats money script keep the database as it stands and set `"syncInitialBankBalance"` to `true` in the pefcl config.json
+ Department pay is still handled by the money script in the config and will need to be configured. (New script coming to address issues with this)
+ DO NOT touch the `"frameworkIntegration"` or the `"identifierType"` section of the pefcl config.lua. It is already set up the way it needs to. 
+ PEFCL does have an app available to use with their phone resource NPWD, you can read more on how to set that up on their docs page.

# COMING SOON
+ I plan to make a ranking script to work with NAT's framework so that payscales may be set different for every rank.
+ Integration with BigDaddy's Personal HUD script.

