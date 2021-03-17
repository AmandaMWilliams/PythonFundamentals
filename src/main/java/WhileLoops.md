#### while

i = 1  
while i <= 5:  
&nbsp;&nbsp;&nbsp;&nbsp; print(i)  
&nbsp;&nbsp;&nbsp;&nbsp; i += 1  
print("Finished")  
// 1  
// 2  
// 3  
// 4  
// 5  
// Finished  
<br>
<hr>

x = 1  
while x < 10:  
&nbsp;&nbsp;&nbsp;&nbsp;if x%2 == 0:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; print(str(x) + " is even")  
&nbsp;&nbsp;&nbsp;&nbsp;else:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; print(str(x) + " is odd")  
&nbsp;&nbsp;&nbsp;&nbsp; x += 1 

1 is odd  
2 is even  
3 is odd  
4 is even  
5 is odd  
6 is even  
7 is odd  
8 is even  
9 is odd  

#### Break
Ends a while loop before the while condition is met  

i = 0  
while 1==1:  
&nbsp;&nbsp;&nbsp;&nbsp; print(i)  
&nbsp;&nbsp;&nbsp;&nbsp; i = i + 1  
&nbsp;&nbsp;&nbsp;&nbsp; if i >= 5:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; print("Breaking")  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; break  

print("Finished")

0  
1  
2  
3  
4  
Breaking  
Finished  

#### continue
Jumps back up to the top of the loop without finishing the remainder of 
the body

i = 0  
while True:  
&nbsp;&nbsp;&nbsp;&nbsp; i = i +1  
&nbsp;&nbsp;&nbsp;&nbsp; if i == 2:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; print("Skipping 2")  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; continue  
&nbsp;&nbsp;&nbsp;&nbsp; if i == 5:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; print("Breaking")  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; break  
&nbsp;&nbsp;&nbsp;&nbsp; print(i)  

print("Finished")  

1  
Skipping 2  
3  
4  
Breaking  
Finished  

