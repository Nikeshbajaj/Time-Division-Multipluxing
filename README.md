# Time Division Multipluxing
## MATLAB Code

## Important to note this that this is a function file not script, you need to pass parameters to execute this program.

#### Step 1.  Save "TDM_nik.m" in your current directory of MATLAB

#### Step 2. define parameter x

#### Step 3. then write  `y=TDM_nik(x)`


### Explaination 

#### x contains all the signals to be multiplexed
#### y is multiplexed signal

#### if you have to mutiplex two signals e.g. x1 and x2 (of course both of same length), if length is not same append zeros in smaller one to make it equal to larger on, then make x(1,:)=x1, x(2,x2)...x(n, xn) (if you have n signals to be multiplexed) then simple run `y=TDM_nik(x)`

Do it 
### Example
#### After saving file in current directory execute following in command window
```
x1 = 1:10
x2 = 10 : -1 : 1
x3(1:5) = 4
x3(6:10) = -4

x(1,:) = x1
x(2,:) = x2
x(3,:) = x3

y = TDM_nik(x)
```


####===========================================
###### If any doubt, confusion or feedback please contact
###### Nikesh Bajaj    http://nikeshbajaj.in
###### bajaj.nikkey@gmail.com
###### PhD Scholar, University of Genova and Queen Mary University of London
