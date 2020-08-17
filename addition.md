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

   Given: The calculator is turned on
   When:  Enter first "number", and then enter second "number", and press "equals".
   Then:  Display "added number" as the intermediate result.
   When:  Again press "add" operator, then enter third "number", then press "equal".
   Then:  Use intermediate result as first number and add third number with this as second number and display the final result.

