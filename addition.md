# Addition

## Scenario: Addition of two positive numbers
  
  Given the calculator is turn on.

  When I type in "positive number", And I press plus.
  And I type in "positive number".
  And I press "equals".
  
  Then I see the "added number" as the result.
  
## Scenario: Addition of two negative numbers

  Given the calculator is turn on.
  
  When I type in "first negative number", And I press plus.
  And I type in "second negative number".
  And I press equal sign.
  
  Then I see the "addition of two numbers with negative sign".
  
## Scenario: Addition of more than 2 numbers

- Given: On the calculator
- When: Enter first "number",
  and then enter second "number",
   and press "equals".
- Then: Display "added number" as the intermediate result.
- When: Again press "add" operator,
         then enter third "number",
         then press "equal".
- Then: Use intermediate result as first number and add third
        number with this as second number and
        display the final result.

## Scenario: Adding numbers where the result goes out of range

- Given: On the calculator
- When: Enter first "number/large size number",
  and then enter "plus" operator,
  and enter second "number/large size number",
   and press "equals".
- Then: Display "Out of range message" as the result.

## Scenario: 6+* as an input

- Given: On the calculator
- When: Enter "6",
  and then enter "plus" operator,
  and enter "star" operator,
   and press "equals".
- Then: Display "Invalid input message" as the result.

## Scenario: Identity operation

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
   and press "equals".
- Then: Use "Identity element" as a second input and add this with first number.
        Display "added number" as the result.

## Scenario: Converse operation

- Given: On the calculator
- When: Enter first "number",
  and then enter "plus" operator,
  and then enter "second" number,
   and press "equals".
- Then: Interchange given input numbers and
        display "added number" as the result.
