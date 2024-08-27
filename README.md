# MDP REPRESENTATION

## AIM:
The representation of real world scenario using Markov Decision Process by stating all the states,actions and environment with respective rewards.

## PROBLEM STATEMENT:
```
Developed By:Challa Sandeep
Registration No: 212221240011
```
### Problem Description
A Man who is standing on the road which is a junction point and thinking about whether to walk left or right

### State Space
{0,1,2} = {Left way,Current position,Right way}

### Sample State
{1} = {Current position}

### Action Space
{0,1,2} = {Walking to left , Being in current position , Walking to right} 

### Sample Action
{2} = {Walking to right}

### Reward Function
+1 If he reaches the goal state that is walking to right way
0 Otherwise

### Graphical Representation
![Rl graph](https://github.com/user-attachments/assets/237ead78-9b53-4f91-9b45-313c83eee2c0)

## PYTHON REPRESENTATION:
```
# Creating Dictionary
P={
    0:{
        0:[(0.0,0,1.0,False)],
        1:[(1,0,1.0,False)]
        
    },
    1:{
        0:[(0,0,0.8,False),(0,2,0.2,True)],
        1:[(1,2,0.8,True),(1,0,0.2,False)]
       
    },
    2:{
        0:[(0,2,1.0,False)],
        1:[(1,2,1.0,False)]
       
    }
}
```

### OUTPUT:
<img width="336" alt="image" src="https://github.com/user-attachments/assets/ed05bc46-d15f-43d9-ad3a-9255d6b6a047">


### RESULT:
Therefore an MDP representation has been created for a real world scenario with all the states, actions and rewards.



