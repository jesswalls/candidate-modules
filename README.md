Module Development Challenge
=================

Fork this repo and clone it into your local development site.

Extend the fundraiser module to allow donors to choose their donation installment period when making a recurring donation. The following options should be presented to the user:

* Monthly
* Quarterly
* Yearly
* Weekly
* 1st and 15th

This task will be evaluated on the following merits:

* Approach taken to add the new installment UI element to the donation form.
* Refactoring ability (e.g., how many tests broke in the process)
* Algorithm used to generate the schedule of future orders
* Correctness of charge dates for the future orders
 
Here are some pointers to get you started.

* The sustainer payment schedule is stored in the fundraiser_sustainers table
* The function _fundraiser_sustainers_create_future_orders() in fundraiser_sustainers.module currently holds the logic to create the future orders
* For payment processing use Commerce’s Payment Method Example module

You may ask for up to 3 assists from Jackson River developers during the evaluation period.
