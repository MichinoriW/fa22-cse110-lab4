1. 3 - this is becuase i has the var declaration, so is it is in the scope at line 12 (function scope)
2. 150 - this is becuase discountedPrice has the var declaration, so is it is in the scope at line 13
3. 150 - this is becuase finalPrice has the var declaration, so is it is in the scope at line 14
4. [50, 100, 150]. This is because the variable discounted gets pushed the discounted prices of prices
5. error - i in line 12 is not in the scope, because i uses the let declaration
6. error - discountedPrice in line 13 is not in the scope, because discountedPrice uses the let declaration
7. 150 - this is because finalPrice has the let declaration, so it is in the scope at line 14 (block scope)
8. [50, 100, 150] - this is because discounted has the let declaration, so it is in the scope.
9. error- i in line 11 is not in the scope because i uses the let declaration
10. 3 - this is because prices is of length 3 and nothing tried to change length
11. [50, 100, 150] - this is because discountedPrice is reset for every iteration of the loop so it technically never changes
12.  
     1. student.name
     2. student['Grad Year']
     3. student.greeting()
     4. student['Favorite Teacher'].name
     5. student.courseLoad[0]
13. 
    1.  32 - because it is string concatenation
    2.  1 - (-) is only works on numbers, so '3' become an integer, then subtracts
    3.  3 - null become 0, so 3+0
    4.  3null - null gets turned into string, then string concatenation of '3'
    5.  4 - true become 1, then 1 + 3
    6.  0 - false and null both become 0
    7.  3undefined - undefined becomes string, then string concatenation of '3' and 'undefined'
    8.  NaN - subtraction only works with numbers, so '3' become 3 and you can't subtract undefined from 3.
14. 
    1.  true - turns '2' into integer, then 2>1
    2.  false - comparing by unicode values, so it compares '2' and '1' first (2<1) which is false
    3.  true - '2' becomes integers, then 2==2
    4.  false - comparing different types, so false
    5.  false - true becomes 1, then 1==2
    6.  true - Boolean(2) returns true, so true==true
15. == changes the type, while === does not.
16. 
17. [2,4,6]. callback refers to doSomething, which multiplies each element by 2. so [1,2,3] becomes [2.4.6].
18. 
19. 1,4,3,2