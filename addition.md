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

  Given that the calculator is ON.
  
  When more than 2 numbers are entered.
  By putting plus sign between 2 consecutive numbers.
  And I press equals sign.
  
  Then I get addition of all number as a result.
