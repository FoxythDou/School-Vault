---
banner: 010 Banners/003 MathBanner.png
banner_x: 0.5
banner_y: 0
---

# Measures of Position

**Date taken:** December 02, 2021
**Original note:** [[007 DN Measures of Position]]
**Previous Note:** [[004 Measures of variability]]
**Following Note:**   [[]]


**Contents:**
- Measures Of Position
- Quartiles
- Deciles
- Percentiles
- Percentile rank

---
### Measures Of Position
- Measures wether something is average, Unusually high or low
- A number that tells where the score is from the others in a set of data.
- Three types
	- Quartiles
	- Deciles
	- Percentiles

```ad-form
**Ungrouped:**
<center>

|  Position  |           Formula            |
|:----------:|:----------------------------:|
|  Quartile  |  $\large c = \frac {kn}{4}$  |
|   Decile   | $\large c = \frac {kn}{10}$  |
| Percentile | $\large c = \frac {kn}{100}$ |
</center>

- $k$ is the value (D6 = 6, P20 = 20)
- $n$ is the number of values

**Grouped:**

$$\large L +  \bigg (\frac {\frac{kn}{i}-cf}{f} \bigg )cw$$

- Where
	- $n$ = Total number of frequency
	- $L$ = Lower Boundary
	- $cw$ = Class Width
	- $cf$ = Culmative frequency of the precedding class
	- $f$ = Frequency of the class
	- $i$ = The measure of position
		- 4 (Quartile)
		- 10 (Decile)
		- 100 (Percentile)
```


##### Quartiles
- Values divided in four
- Think of Q1, Q2, Q3 as the slice that divides the whole thing to 4
<span class='centerImg'> ![[Pasted image 20211202171222.png|600]] </span>

##### Deciles
- Values divided by ten

##### Percentiles
- Values divided by one hundred
---
### How to solve (Generally the same for all measures)
- **Ungrouped:**
	- Find the Q1 of 3, 9, 12, 13, 15, 17, 19, 20, 24
	
<span class='centerImg'> ![[Pasted image 20211208181409.png|200]]</span>
```ad-note

<span class='centerImg'> ![[Pasted image 20211202123045.png|300]]  </span>

- *Im unsure about this part but eh, the example is below im lazy lmao*
```


<span class='centerImg'> ![[Pasted image 20211202123146.png|400]]</span>

- **Grouped:**

<span class='centerImg'> ![[Pasted image 20211208183228.png|250]]</span>
1.  Firstly we solve the $\LARGE \frac {kn}{i}$. Remember this time, $n$ is the total frequency.


<span class='centerImg'> ![[Pasted image 20211208183443.png|200]]</span>


2. After getting our answer, we would find the $cf$ nearest to that. It is 9, But we should pick 1 class above (20 in this case) . So that is how we will get the $L$, and $f$
	- $L = 22.5$ 
	- $f = 11$
- For $cf$ we will be taking the it from the previous class.	
	- $cf = 9$

3. After which, we would substitute and tadaa!


<span class='centerImg'> ![[Pasted image 20211208184412.png|200]] </span>

> 25% of the students who took a test got a score equal or less than 24 
- We rounded it off, That is why instead of our answer being 23.05
---

### Percentile Rank (Only Ungrouped)
```ad-form
$$rank =  \bigg ( \frac {A + 0.5}{n}\bigg ) 100$$


**Where:**
- $A$ = Number of values below x
- $n$ = Number of data
```
 
<span class='centerImg'> ![[Pasted image 20211208185906.png|500]]</span>

```ad-note

<span class='centerImg'> ![[Pasted image 20211202123203.png|400]]  </span>

```
---
<br></br>