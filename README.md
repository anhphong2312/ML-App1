# ML-App1
answer the question, “Will a customer accept the coupon?”

Observations
1. User attributes
    -  Gender: male, female: 
       -  there is no real difference among genders of male vs female for coupon decisions
       -  !["gender"](.\assignment_5_1_starter\images\gender.png)

    -  Age: below 21, 21 to 25, 26 to 30, etc.
       -  from the pie chart, the groups of _**age under 30**_ make up ~50% of the coupon decisions. We should focus on targeting this group.
       -  !["age"](.\assignment_5_1_starter\images\age.png)  
    -  
    -  Marital Status: single, married partner, unmarried partner, or widowed
        - there are no real difference among single vs married/unmarried partner in this decision making.
        -  !["Marital Status"](.\assignment_5_1_starter\images\maritalStatus.png)  
    -  Number of children: 0, 1, or more than 1
        - those who _**have children**_ are more sensitive to buying coupons.
        -  !["children"](.\assignment_5_1_starter\images\has_children.png)  
    -  Education: high school, bachelors degree, associates degree, or graduate degree
        - those who have bachelor degrees or still in colleges made up the majority of the coupon usage.
        -  !["education"](.\assignment_5_1_starter\images\education.png)  
    -  Occupation: architecture & engineering, business & financial, etc.
    -  
    -  Annual income: less than \\$12500, \\$12500 - \\$24999, \\$25000 - \\$37499, etc.
    -  
    -  Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    -  
    -  Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    -  
    -  Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    -  
    -  Number of times that he/she eats at a restaurant with average expense less than \\$20 per person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    -  
    -  Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8
    

2. Contextual attributes
    - Driving destination: home, work, or no urgent destination
    - 
    - Location of user, coupon and destination: we provide a map to show the geographical
    location of the user, destination, and the venue, and we mark the distance between each
    two places with time of driving. The user can see whether the venue is in the same
    direction as the destination.
    
    - Weather: sunny, rainy, or snowy
    - 
    - Temperature: 30F, 55F, or 80F
    - 
    - Time: 10AM, 2PM, or 6PM
    - 
    - Passenger: alone, partner, kid(s), or friend(s)


[def]: gender