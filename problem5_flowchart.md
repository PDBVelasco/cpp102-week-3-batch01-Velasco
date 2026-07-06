~~~ mermaid
[START] --> Input
Input --> Num1
Input --> Num2 
Num1 --> Price1
Num2 --> Quantity1
Price1 --> Multiply
Quantity1 --> Multiply
Multiply --> Product
Product --> Item1 
Item1 --> If_more_items
If_more_items --> Input
Item1 --> If_none
If_none --> Print_total
Print_total --> [End]