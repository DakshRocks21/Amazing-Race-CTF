## Starbucks

### Description
You are a barista at Starbucks. Most customers are quite clear in their orders but one is not. He keeps stuttering and is very unclear with his orders.

As a barista equipped with professional coding skills, you have to create a program to find the words "cappuccino", "espresso" and "mochalatte" in the order of the stuttering and nervous customer. You will then output the amount of cappuccino, espresso and mocha latte the customer wants.

Input: a txt file
The flag is in the format FLAG{x:y:z} where x is the amount of cappuccino, y is the espresso, z is the mochalatte. 0 ≤ x,y,z ≤ 100000

**Examples**:<br>
_Example 1_:<br>
Input: `ajsjdjajfcappuccinololos`<br>
Flag:  `FLAG{1:0:0}`

Explanation:<br>
In the string `ajsjdjajfcappuccinololos` there is 1 cappuccino inside it and 0 mochalatte and espresso, hence outputting "1:0:0"

_Example 2_:<br>
Input: `Uhh.Alatteplsand2mochalattesand5?!?ugh20espresso`<br>
Flag: `FLAG{0:1:1}`

Explanation:<br>
In the string `Uhh.Alatteplsand2mochalattesand5?!?ugh20espresso`, mochalatte and espresso appears once each. You do not need to care about the number in front of them as we are checking how many times these specific types of coffee appear.
Please download the template.py file and the txt file.

### Files
https://drive.google.com/drive/folders/1h3uYH_dzsNooRxmvRfppqXNjq209S9EE?usp=sharing
