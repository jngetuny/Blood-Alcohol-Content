# Blood-Alcohol-Content
Blood alcohol content (BAC) is a measure of how much alcohol is in someone’s blood.
Blood alcohol content (BAC) is a measure of how much alcohol is in someone’s blood. It is usually measured as a percentage, so a BAC of 0.3% is three-tenths of one percent. That is, there are 3 grams of alcohol for every 1,000 grams of blood. A BAC of 0.05% impairs reasoning and the ability to concentrate. A BAC of 0.30% can lead to a blackout, shortness of breath, and loss of bladder control. In most states, the legal limit for driving is a BAC of 0.08%.
BAC is usually measured by a breathalyzer, urinalysis, or blood test. However, Swedish physician E. M. P. Widmark developed the following equation for estimating an individual’s BAC. This formula is widely used by forensic scientists.
B = -0.015*t+ ├ ( (2.84*N)/(W*g)┤)

The variables in the formula are defined as:
B = percentage of BAC
N = number of “standard drinks” (N should be at least 1)
(NOTE: A standard drink is one 12-ounce beer, one 5-ounce glass of wine, or one 1.5-ounce shot of distilled liquor.)
W = weight in pounds
g = gender constant, 0.68 for men and 0.55 for women
t = number of hours since the first drink
Consider the case of a male student who has five beers and weighs 180 pounds. Do you need any additional information to estimate his BAC?
Use the formula to estimate BAC for this student one, three, and five hours after his first drink. What pattern do you observe in the results?
Write a Python computer program that prompts your user for the elements needed to estimate Blood Alcohol Content using the Widmark formula above.
The program should allow your user to continue to make Blood Alcohol Content estimates until they enter a sentinel value. Be sure to inform your user what that sentinel value is. Validate all the user input values. Use the following table to determine which of the possible effects corresponds to the BAC value that was calculated.

BAC Estimate	Possible Effects
Less Than 0.03%	Normal behavior, no impairment
0.03% or greater, but less than 0.06%	Mild euphoria and impairment
0.06% or greater, but less than 0.10%	Euphoric, increased impairment
0.10% or greater, but less than 0.20%	Drunk, loss of motor control
0.20% or greater, but less than 0.30%	Confused, possible blackout
0.30% or greater, but less than 0.40%	Possibly unconscious
0.40% or greater	Unconscious, risk of death

Display the BAC value and the possible effects that correspond to that value.
The legal limit for driving is a BAC of 0.08%. If the BAC value is 0.08% or greater, also display a phrase like “Over the legal limit for driving.”
