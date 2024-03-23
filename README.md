# WHMCS Discord Notification Hook
Want instant Discord notifications? Need to know when you've received a ticket reply without waiting for emails to give you a notification? This hook will allow just that! open-source and customisable - offering a range of instant notifications within your Discord server. 

## Discord Notification
> ## tadashijei.com - Tadashi Jei / FullStack Developer / PHP / WHMCS / ETC.

## Installation Instructions
1. Download a free copy of this GitHub repo or release version; you should end up with a `.zip` file.
2. Extract the file and upload the `includes` folder within the zip to your base WHMCS directory (we'd recommend doing so on a development environment first).
3. Open up the file you have just uploaded, which will be within the `includes/hooks` directory. The full path is `includes/hooks/WHMCS-Discord-Notifications.php`
4. Modify lines `11-41` to enter your Discord configuration. Comments are provided below each option to assist you in understanding what data is needed for each.
5. Modify lines `42-74` to your liking to enable or disable which notifications are sent by the hook to your Discord server.
6. Give it a test! Check to make sure it sends through to the channel configured within your Discord server; if it doesn't work, double-check your config options! **Enjoy!**

## Configuration Options
* Set a specific rank depending on the notification type to get pinged to deal with it.
* Automatically generated link to instantly navigate to the page the notification is relating to.
* Configurable name of the bot sending messages.
* Configurable avatar profile image (allowing the same webhook to be used by multiple installs).
* Configurable message colours.

## Notification Types
### Ticket Notifications
* New Ticket Opened
* New Ticket Reply Received
* New Ticket Note
* Ticket Flagged To Staff Member  

### Invoice Notifications
* Invoice Payment Received
* Invoice Refunded
* Invoice Late Fee Added  

### Order Notifications
* Order Marked as Pending
* Order Paid
* Order Accepted
* Order Marked As Fraudulent
* Order Cancelled
* Order Cancelled and Refunded  

### Network Issue Notifications
* New Network Issue
* Network Issue Modified
* Network Issue Closed

### Misc Notifications
* Cancellation Request Received 
