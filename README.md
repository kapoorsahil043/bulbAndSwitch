# bulbAndSwitch program

This is program counts the no. of instances when bulb glows, as and when we perform switch On.
Initially all bulb will be off.

Note - all previous switches have to be turned On, for that particular bulb to glow.

Eg. 
we have 5 bulbs and all are turned Off initially.
bulb = [0,0,0,0,0].

So, if we turn On bulb 2, then bulb 1 has to be On, for that bulb to glow.
Eg.
bulb = [0,1,0,0,0] - it won't glow the bulb, though switch 2 is On.

bulb = [1,1,0,0,0] - Now, bulb 1 & 2 will glow as we have turned On switch 1. 

Here, we need to count the no. instances when bulb glows.
In above case, the instance will be 1;

Eg. switch = [2, 3, 1, 5, 4] - in this case, the 2 times bulb will glow.

This is an optimzed and simple program.
Enjoy!!.





