# reCAPTCHA V3 for Prestashop 1.6 and 1.7
This module is a branch of pdrecaptcha created by Prestademia
Module originally is compatible with PS versions 1.6 and 1.7

Please check main branch for more details.

Changes made in this branch to the main branch:
Added CAPTCHA verification option for customer registration page using the hook 
# actionSubmitAccountBefore
You will find a new switch button in module configuration page to enable or disable reCAPTCHA on customer registration page.

This hook is available since PS 1.7.1+
So this addition will work on the above mentioned version of prestashop and above.
For all other versions, we will need an override.

This is initialization of the project. Depending on number of users and their requests, we can further refine and make it backward compatible for prestashop versions older than 1.7.1.

Please try and let us know about issues. There is no proven method to TEST the working on CAPTCHA, although it might appear on the page. So please implement it, after few days check your Google reCAPTCHA dashboard to learn if the module is doing its work.
Advertencia!

Please follow main branch for any additional instructions.

Thank you!
