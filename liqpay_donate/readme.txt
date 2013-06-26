Developer: Kirill Danilevsky, k.danilevsky@gmail.com

This module will help organize the following functionality:

Installation anywhere in the site block in which you can make a donation. Namely, the user submits their name, your phone number, e-mail address, amount of donation, which he wants to do for the site, and select a payment system through which it can take a donation.
After clicking on the "Donate", the user will be forwarded to a page or votes (if the payment is automatic) or first to the payment site to make a payment, and after that to the page thanks.

In the admin menu, under «Configuration" item will be «Donate settings" when you click on a form that will display the settings for managing payments and payment systems.

In the left column are derived form tabs, each of which corresponds to their payment system.

In the first version of the module will be available as long as only one payment system - LiqPay.

When you select a payment system will be available fields to edit the payment system:

LiqPay:

Title - text with a brief description of what the payment system
Signature - the signature of the payment system LiqPay (issued payment system)
Merchant_id - identification number in the payment system (provided by the payment system)
Site URL - to which reference is to redirect the user when you click on the button «Donate»
Active - If this box is marked, the system is active and will be available for selection in the unit at the time of donation.

The lower part of the form contains the settings tab «Thanks text». Here in the text field, you can put text votes, which will be displayed to the user after they made the donation.

In subsequent versions of the module functionality and settings will be expanded.

For the analysis of donations committed there must be statistics. Statistics are available in the admin menu in «Reports» paragraph «Donate report».
These statistics are in fact in a table (List of those who made a donation). This table has the following fields:
Name - name of the person, which he introduced when making donations
Amount UAH - perfect amount of donations to the Ukrainian hryvnia
Status - a status which is now in charge. Not paid - not paid, Paid - paid
Payment system - a payment system through which payment
E-mail - e-mail address of the user, which he introduced when making donations
Phone - user's phone number, which he introduced in the commission of donations
Date - date of the donation

In the table, you can do the sorting by any field. To do this, you can click on the header fields and sorting will be carried out in this field. This can be sorted in ascending and descending order.

In a subsequent version of the module will add another payment system and make your address book. The address book can contain people or organizations for which you can configure a separate process donations. 