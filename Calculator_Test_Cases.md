# 🧮 Calculator Application – Test Cases

---

## TC_01 – Addition of Two Positive Numbers

**Test Case ID:** TC_01  
**Test Description:** Verify addition of two positive integers  
**Preconditions:** Calculator application is launched  

**Test Steps:**
1. Enter first number as 10  
2. Enter second number as 5  
3. Click on "+" button  
4. Click on "=" button  

**Expected Result:**  
Result should display 15  

---

## TC_02 – Subtraction of Two Negative Numbers

**Test Case ID:** TC_02  
**Test Description:** Verify subtraction of two negative numbers  
**Preconditions:** Calculator application is launched  

**Test Steps:**
1. Enter first number as -8  
2. Enter second number as -3  
3. Click on "-" button  
4. Click on "=" button  

**Expected Result:**  
Result should display -5  

---

## TC_03 – Multiplication with Decimal Numbers

**Test Case ID:** TC_03  
**Test Description:** Verify multiplication of decimal numbers  
**Preconditions:** Calculator application is launched  

**Test Steps:**
1. Enter 2.5  
2. Enter 4.0  
3. Click on "*" button  
4. Click on "=" button  

**Expected Result:**  
Result should display 10.0  

---

## TC_04 – Division by Zero (Invalid Case)

**Test Case ID:** TC_04  
**Test Description:** Verify division by zero handling  
**Preconditions:** Calculator application is launched  

**Test Steps:**
1. Enter 10  
2. Enter 0  
3. Click on "/" button  
4. Click on "=" button  

**Expected Result:**  
Error message should display "Cannot divide by zero"  

---

## TC_05 – Invalid Input (Alphabet Characters)

**Test Case ID:** TC_05  
**Test Description:** Verify system behavior when alphabetic input is entered  
**Preconditions:** Calculator application is launched  

**Test Steps:**
1. Enter "abc"  
2. Click on "+" button  
3. Enter 5  
4. Click on "=" button  

**Expected Result:**  
System should show validation error  

---

## TC_06 – BODMAS Rule Validation

**Test Case ID:** TC_06  
**Test Description:** Verify correct BODMAS calculation  
**Preconditions:** Calculator application is launched  

**Test Steps:**
1. Enter expression: 2 + 3 × 4  
2. Click on "=" button  

**Expected Result:**  
Result should display 14  

---
