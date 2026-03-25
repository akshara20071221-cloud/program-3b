# program-3b
# 🧪 C Programming Lab
## 📘 Experiment No: 3b
### 🔹
**Date:** 1/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
To write a C program to check whether a given number is a armstrong number or not.
---

## 🧠 ALGORITHM
1 Get a number as input from the user.
2 Check whether the number is armstrong or not by using looping statements.
3 print the result using printf() function.
---

## 💻 PROGRAM

```
#include<stdio.h>
#include<math.h>
int main()
{
    int num,org,n=0,sum=0;
    scanf("%d",&num);
    org=num;
    for(int i=num;i!=0;i/=10)
    {
     n++;   
    }
    for(int i=num;i!=0;i/=10)
    {
       sum+=pow(num%10,n); 
    }
    if(sum==org)
    printf("%d is a armstrong number",org);
    else
    printf("%d is not a armstrong number",org);
    
}

```

## 🖼️ OUTPUT SCREENSHOT
<img width="805" height="158" alt="image" src="https://github.com/user-attachments/assets/b66d7bb2-e583-46af-b309-6fd0aa0150ee" />

---

## ✅ RESULT
: Thus the C program to check whether the given number is a armstrong number of not is executed successfully.
