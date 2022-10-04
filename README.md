# Random-User-API-Performance-Test-Using-JMeter

## Here I tried to find the actual TPS for a site with a given number of users and time frame. Then I tried to find out the bottleneck/stress test point. (At which point the system starts to show 1% error).
   - Site Tested: https://random-data-api.com/api/v2/users
   - Number of User: 120000
   - Timeframe: 12 Hours

## Tools / Technology Used
  - JMeter
  
## Scenario
  - Find the Actual TPS
  - Compare it with Expected TPS
  - Find out the Bottleneck/Stress test point
  
## Prerequisite
  - Java must be installed (Preferred version 8 or 11)
  
## How to run this project
  - Clone this project
  - Open the jmx file using JMeter
  - Test with different time frame and users to find the target value
  
## TPS calculation
  Link to Excel: https://docs.google.com/spreadsheets/d/1vXmt8wqHG2fu20Oi9BXjAFT6WOuR49V5/edit?usp=sharing&ouid=105382160112398553095&rtpof=true&sd=true
  
## Bottleneck Calculation
  Link to Excel: https://docs.google.com/spreadsheets/d/1avNDcD3mrQwyRyzkYMyFzf4syFWdhXFX/edit?usp=sharing&ouid=105382160112398553095&rtpof=true&sd=true
  
## TPS Output 
  - First break down the process
  -  ![image](https://user-images.githubusercontent.com/52327199/193750352-72122d5d-00f0-41de-8880-f94d5a51f324.png)
  - Perform tests with different number of users and timeframe
  - ![image](https://user-images.githubusercontent.com/52327199/193750610-afa73baf-0126-4e1a-bbb8-399e025262ef.png)
  - Compare 
  - ![image](https://user-images.githubusercontent.com/52327199/193750690-9a8a7ae5-c0ee-4170-83dc-3217db619589.png)

## Bottleneck Output
  - First break down the process
  -  ![image](https://user-images.githubusercontent.com/52327199/193750352-72122d5d-00f0-41de-8880-f94d5a51f324.png)
  - Perform tests with different number of users with same timeframe
  - ![image](https://user-images.githubusercontent.com/52327199/193750922-2289b62c-681f-478f-8672-cd1b88a4a0f5.png)
  - Findout where it starts to show 1% error 
  - ![image](https://user-images.githubusercontent.com/52327199/193751092-73b8284a-f947-4e03-923c-63f8bdcd7cc7.png)

