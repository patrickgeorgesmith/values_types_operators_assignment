# Values, Types & Operators Exercises

## Problem One

What are the types of the following expressions and what do they evaluate to, and why?
```
* `17`  String - String are in quotes - Evalutes to '17'
* `1 + 2 * 3 + 4` - Number - Evaluates to 11 - Order of Operations
* `800 / 80 / 8` - Number - Evaluates to 1.25 - Order of Operations
* `400 > 200` - Boolean - Evaluates to true - 400 is greater than 200
* `1 !== 1` - Boolean - Evaluates to False - 1 is equal to 1
* `true || false` Booelean - Evaluates to true - One side is ture
* `true && false` Boolean - Evaluates to false - Not true
* `20 % 6` Number - Evaluates to 2 - Modulo is 2 
* `'a' + 'b'` String - Evaluates to 'ab' - Concatenation
```
## Problem Two

What will the following return?
```
* `typeof 4` - Number
*  `typeof 'hello'` - String
*  `typeof true` - Boolean 
* `2 === 1 || 3 === 4` - False
```
## Problem Three

Create a truth table for the expression A || B.

```

|   A   |   B   | A || B | 
|-------|-------|--------|
| true  | true  |  true  |
| false | true  |  true  |
| true  | false |  true  |
| false | false |  false | 

```

## Problem Four

Create a truth table for the expression !A && !B.

```
|   A   |   B   | !A && !B | 
|-------|-------|--------|
| true  | true  | false  |
| false | true  | false  |
| true  | false | false  |
| false | false | true   |

````
## Problem Five

Create a truth table for the expression !(A || B).
```
|   A   |   B   | ! (A || B )|
|-------|-------|--------|
| true  | true  |  false |
| false | true  |  false |
| true  | false |  false |
| false | false |  true  | 
```


## Problem Six

Write a step-by-step evaluation for the following expression (remember order of operations): 2 + 3 * 2 + 1.

  ```
  2 + 3 * 2 + 1
    2 + 6 + 1
        8 + 1
            9

```
 ## Problem Seven
 
 Write a step-by-step evaluation for the following expression (remember order of operations): 4 / 2 + 8 / 4.
  ```
   4 / 2 + 8 / 4
        2 + 2
            4
  ```


 ## Problem Eight
 
 Write a step-by-step evaluation for the following expression: 'ca' + 'ter' + 'pi' + 'llar'.
    
```  
'ca' + 'ter' + 'pi' + 'llar'
      cater + 'pi' + 'llar'
                caterpillar
```    

 ## Problem Nine
 
 Write a step-by-step evaluation for the following expression: 2 * 4 === 8 && 'car' + 'pool' === 'carpool'.
        
        
  ```    
  8 === 8 && 'car' + 'pool' === 'carpool'
  true && true
  true
  ```      
        


 ## Problem Ten
 
  Write a step-by-step evaluation for the following expression: '1' + '2' + '3' - '1'
    
  ```
  1' + '2' + '3' - '1'`
  122
  ```  

  
    




    