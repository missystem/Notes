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
* Definition of modular operator<br>
Let a, r, m ∈ ℤ, and m > 0, then we write a ≡ r mod m if m divides (a-r), i.e. m|(a-r) <br>
here m = modulus, r = remainder
	 - Example: 
	 ```
	 a = 13, m = 9<br>
	 r = ?  
	 13 ≡ 4 mod 9  
	 a-r = (13-4) = 9
	 ```  




