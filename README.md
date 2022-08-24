
## Finding Best Algorithms For Vehicle Coupon Recommendation Dataset


## Data Set Information:

This data was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. For more information about the dataset.

## Attribute Information:

Destination: No Urgent Place, Home, Work

Passanger: Alone, Friend(s), Kid(s), Partner (who are the passengers in the car)

Weather: Sunny, Rainy, Snowy

Temperature:55, 80, 30

Time: 2PM, 10AM, 6PM, 7AM, 10PM

Coupon: Restaurant(<$20), Coffee House, Carry out & Take away, Bar, Restaurant($20-$50)

Expiration: 1d, 2h (the coupon expires in 1 day or in 2 hours)

Gender: Female, Male

Age: 21, 46, 26, 31, 41, 50plus, 36, below21

MaritalStatus: Unmarried partner, Single, Married partner, Divorced, Widowed

Children:1, 0

Education: Some college - no degree, Bachelors degree, Associates degree, High School Graduate, Graduate degree (Masters or Doctorate), Some High School

Occupation: Unemployed, Architecture & Engineering, Student, Education&Training&Library, Healthcare Support, Healthcare Practitioners & Technical, Sales & Related, Management, Arts Design Entertainment Sports & Media, Computer & Mathematical, Life Physical Social Science, Personal Care & Service, Community & Social Services, Office & Administrative Support, Construction & Extraction, Legal, Retired, Installation Maintenance & Repair, Transportation & Material Moving,Business & Financial, Protective Service,Food Preparation & Serving Related, Production Occupations,Building & Grounds Cleaning & Maintenance, Farming Fishing & Forestry.

Income: $37500 - $49999, $62500 - $74999, $12500 - $24999, $75000 - $87499, $50000 - $62499, $25000 - $37499, $100000 or More, $87500 - $99999, Less than $12500.

Bar : never, less1, 1~3, gt8, nan4~8 (feature meaning: how many times do you go to a bar every month?)

CoffeeHouse : never, less1, 4~8, 1~3, gt8, nan (feature meaning: how many times do you go to a coffeehouse every month?)

CarryAway:n4~8, 1~3, gt8, less1, never (feature meaning: how many times do you get take-away food every month?)

RestaurantLessThan20: 4~8, 1~3, less1, gt8, never (feature meaning: how many times do you go to a restaurant with an average expense per person of less than $20 every month?)

Restaurant20To50: 1- 3 , less1, never, 4 -8, nan (feature meaning: how many times do you go to a restaurant with average expense per person of $20 - $50 every month?)

toCoupon_GEQ15min:0,1 (feature meaning: driving distance to the restaurant/bar for using the coupon is greater than 15 minutes)

toCoupon_GEQ25min:0, 1 (feature meaning: driving distance to the restaurant/bar for using the coupon is greater than 25 minutes)

direction_same:0, 1 (feature meaning: whether the restaurant/bar is in the same direction as your current destination)

direction_opp:1, 0 (feature meaning: whether the restaurant/bar is in the same direction as your current destination)

Y:1, 0 (whether the coupon is accepted)

## References:
<a id="1">[1]</a> Wang, T., Rudin, C., Doshi-Velez, F., Liu, Y., Klampfl, E., & MacNeille, P. (2017). A Bayesian Framework for Learning Rule Sets for Interpretable Classification. J. Mach. Learn. Res., 18, 70:1-70:37.
[https://jmlr.org/papers/volume18/16-003/16-003.pdf]
