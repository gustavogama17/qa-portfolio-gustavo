# Test Cases – Product Search (E-commerce)

This document contains functional test cases created to validate the product search feature of an e-commerce platform.

---

## CT-PRO-01 – Search with valid product name

**Pre-condition:**  
User has access to the website and the search field is available.

**Steps:**  
1. Access the e-commerce home page  
2. Enter a valid product name in the search field  
3. Click on the “Search” button  

**Expected result:**  
The system should return a list of products related to the searched term.

**Status:** Pass

---

## CT-PRO-02 – Search with non-existent product

**Pre-condition:**  
User has access to the website and the search field is available.

**Steps:**  
1. Access the e-commerce home page  
2. Enter a non-existent product name in the search field  
3. Click on the “Search” button  

**Expected result:**  
The system should display a message informing that no products were found.

**Status:** Pass

---

## CT-PRO-03 – Search with empty search field

**Pre-condition:**  
User has access to the website and the search field is available.

**Steps:**  
1. Access the e-commerce home page  
2. Click on the search field  
3. Do not enter any characters  
4. Click on the “Search” button  

**Expected result:**  
The system should display a validation message or show a default behavior (such as most searched or best-selling products), without errors.

**Status:** Pass

---

## CT-PRO-04 – Search with special characters

**Pre-condition:**  
User has access to the website and the search field is available.

**Steps:**  
1. Access the e-commerce home page  
2. Click on the search field  
3. Enter special characters (e.g. @#$%)  
4. Click on the “Search” button  

**Expected result:**  
The system should handle the input correctly, displaying a message that no products were found or applying a defined default behavior, without generating errors.

**Status:** Pass
