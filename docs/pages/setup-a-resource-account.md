## Setup a Resource Account
#### Steps
1. Log into the Teams Admin Portal 
   - https://admin.teams.microsoft.com/ 
1. Navigate to **Org-wide settings** > **Resource accounts** 
1. Select **+** Add 
1. Enter in a **Display name**, **Username** and **Resource account type** 
   - It’s recommended to start *display names* and *usernames* with either RACQ_ (Call Queue) or RAAA_ (Auto Attendant) so they are grouped together and identifiable in large user lists. 
1. Select the domain name associated with the Direct Routing provider as the username’s domain name (EG `@customer.sbcconnect.com.au`)
   - The Call Queue called 'Accounts' for the customer `CONTOSO` would have the following details
     - Name: `RACQ_Accounts`
     - Username: `RACQ_Accounts@contoso.sbcconnect.com.au`
1. Click Save 



## Obtain the Phone System-Virtual User License 

This license is required ONLY when a Call Queue or Auto Attendant has an inbound phone number. Nested Call Queues or Auto Attendants do not require a license because they don’t have a publicly callable phone number assigned to them. 

### Notes
- *Instructions are written in the new Admin Center Preview*
- *Staff of a Microsoft Cloud Service Provider can issue these licenses from the Microsoft Partner Portal at https://partner.microsoft.com*

#### Steps
1. Log into the Microsoft Admin Center 
   - https://admin.microsoft.com 
1. Navigate to **Billing** > **Purchase Service** 
1. Scroll to the bottom of the page and select **Add-ons** 
1. Locate and click the **Phone System – Virtual User** license that will be Free 
1. Select **Pay for a full year** 
1. Increase the QTY to **25** or the number required if higher 
   - By default, you can get 25 free licenses then 1 additional license for every 10 users licensed in Office 365 with a Phone System license (E5 License -OR- E1/E3 + Phone System) 
1. Untick **Automatically assign to all of your users with no licenses** 
1. Click **Check out now** 
1. Confirm the order and click **Next** 
1. Select the **Payment method** of **Invoice (pay by bank transfer only)**
1. Don’t complete any further information then click **Place Order** 
1. Once complete, you’ll be presented with a **You’re all set!** Screen 


##Assign the Phone System-Virtual User License to the Resource Accounts 
#### Steps
1. Log into the Microsoft Admin Center 
   - https://admin.microsoft.com 
1. Navigate to **Users** > **Active users** 
1. Locate and select the resource account 
1. Select **Licenses and Apps** 
1. Select **Australia** from the **Select location** drop down list 
1. Tick the license **Phone System – Virtual User**
1. Click **Save changes** 
