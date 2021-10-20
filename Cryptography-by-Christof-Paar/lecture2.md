# Lecture 2 - Modular Arithmetic and Historical Ciphers

## Topic today:
* Modular Arithmetic
* Rings
* Shift Cipher
* Affirm Cipher

---

## 1. Modular Arithmetic
* Goal: Computation in *finite* sets
* Example: For a finite set in everyday life
	- clock is finite<br>
	```
	   12
	+  20
	-----
	   32

	12+20 ≡ 8 mod 24
	```
### **Definition of modular operator**<br>
Let a, r, m ∈ ℤ, and m > 0, then we write a ≡ r mod m if m divides (a-r), i.e. m|(a-r) <br>
here m = modulus, r = remainder
	 - Example: 
	 ```
	 a = 13, m = 9, r = ?  
	 13 ≡ 4 mod 9  
	 a-r = (13-4) = 9
	 ```  
* 1a) Computation of the remainder<br>
Given: ```a, m ∈ ℤ```<br>
write ```a = qm```<br>
here q = quotient<br>
	 - Example:```a = 42, m = 9```
	  ```
	  42 = 4 * 9 + 6 => r = 6
	  check: (42-6)=36, 9|36 √
	  ```
	  but also
	  ```
	  42 = 3 * 9 + 15 => r = 15
	  check: (42-15)=27, 9|27 √
	  ```
	  but also
	  ```
	  42 = 5 * 9 + (-3) => r = -3
	  check: (42-(-3))=45, 9|45 √
	  ```
==> **The remainder is not unique**
	  ```
	  42 ≡ 6 mod 9
	  ```
* 1b) Equivalence Classes
- Example



