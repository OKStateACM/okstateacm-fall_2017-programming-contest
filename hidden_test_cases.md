# Okstate ACM Programming Contest Fall 2017 Hidden Test Cases

## Problem 1
  - Input: <kbd>Go Pokes</kbd>
    <br>
    Output:
    ```
    s
     e
      k
       o
        p
         
          o
           G
    ```

  - Input: <kbd>Example string</kbd>
    <br>
    Output:
    ```
    g
     n
      i
       r
        t
         s
          
           e
            l
             p
              m
               a
                x
                 E
    ```

## Problem 2
  - Input1: <kbd>hello</kbd>
    <br>
    Input2: <kbd>byffi</kbd>
    <br>
    Output: 20

  - Input1: <kbd>contest</kbd>
    <br>
    Input2: <kbd>qcbhsgh</kbd>
    <br>
    Output: 14

  - Input1: <kbd>caesar</kbd>
    <br>
    Input2: <kbd>caesar</kbd>
    <br>
    Output: 0 **or** 26
    
## Problem 3
  - Input: <kbd>5 hello the sun is cool</kbd>
    <br>
    Output:
    ```
    olleh hello
      eht the
      nus sun
       si is
     looc cool
    ```

  - Input: <kbd>3 bananas chocolate alkatraz</kbd>
    <br>
    Output:
    ```
      sananab bananas
    etalocohc chocolate
     zartakla alkatraz
    ```

## Problem 4
  - This will be a bit hard, since you will need to edit files. Just make sure you type everything down correctly.

  - Input File:
    ```
    0 4 5 6
    1 2 3 4
    4 3 2 1
    7 5 4 0
    ```
    Output: Yes, this is palindromic

  - Input File:
    ```
    0 5 5 9
    1 8 7 3
    0 9 8 2
    5 4 3 1
    ```
    Output: No, this is not palindromic

## Problem 5
  - Input:
    ```
    2 3
    1 1
    1 2 3
    ```
  - Output:
    ```(1, 2), (1, 3)```

  <hr>
  
  - Input:
  ```
  10 20
  1 2 3 4 5 6 7 8 9 10 3
  1 2 3 4 5 6 7 8 9 10 1 1 1 1 1 1 1 1 1 1
  ```
  - Output:
  ```
  Not enough boots!
  ```

  <hr>

  - Input:
  ```
  20 21
  1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20
  21 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 
  ```

  - Output:
  ```
  (1,2), (2,3), (3,4), (4,5), (5,6), (6,7), (7,8), (8,9), (9,10),
  (10,11), (11,12), (12,13), (13,14), (14,15), (15,16), (16,17),
  (17,18), (18,19), (19,20), (20,21)
  ```

## Problem 6
  - Input: <kbd>196418</kbd>
  - Output: 16
  <hr>
  - Input: <kbd>46</kbd>
  - Output: 46 is not in the fibonacci sequence before 45
  <hr>
  - Input: <kbd>24157817</kbd>
  - Output: 77

## Problem 7
  - Test with n = 300 as well as two other random values of n from the attached file

## Problem 8
  - Input:
  ```
  6
  ..R...
  .XXXX.
  .XHXX.
  ....X.
  ......
  ......
  ```
  - Output:
  ```
  DLLUUURR
  ```

  <hr>
  
  - Input:
  ```
  9
  H........
  .........
  .........
  .........
  .........
  .........
  .........
  .........
  ........R
  ```
  - Output (not unique): 
  ```
  DDDDDDDDRRRRRRRR
  ```

## Problem 9
  - Input (this is a corner case):
  ```
  H = 1, W = 1
  5
  ```
  - Output:
  ```
  Cost = 5
  _blank_
  ```

  <hr>
  
  - Input:
  ```
  H = 2, W = 1
  7
  2
  ```
  - Output:
  ```
  Cost = 9
  U
  ```

  <hr>
  
  - Input:
  ```
  H = 3, W = 4
  2 4 6 9
  3 1 2 4
  8 5 3 1
  ```
  - Output:
  ```
  Cost = 27
  U, R, R, R, U
  ```

## Problem 10
  - Again, this one will be time consuming to judge. Thankfully it's designed so you probably won't have to do it often. Just make sure you type everything down correctly.
  
  - **NOTE**: Do not include the spaces I put between each charater, that is just used to better tell how many underscores there are

  - Input File:
  ```
  R " a p p l e s " D
  Q _ _ P P P P P P L
  ```
  Output:
  ```
  selppa
  ```

  - Input File (There is just one space between the "", sorry it's kind of confusing):
  ```
  R D _ P "   " L _ _
  _ R _ _ _ _ _ _ D _
  D " h e l l o " L _
  R P P P P P 0 7 J Q
  ```
  Output:
  ```
  hello hello
  ```
