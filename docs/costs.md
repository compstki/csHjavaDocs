# Instructions `Costs`

## about
This task assumes that you have already been introduced to:
* using parallel arrays

> There is some `PRIMM` code to guide you throught the steps in the task. 

> Try to work with a partner and _discuss_ your code _before_ typing and running the code.

> _Make sure your output is **correct** before moving from one stage to the next, ask your teacher if you need some assistance._

---

### `predict`

> modulo is the integer remainder after an integer is divided by another integer, so `10` modulo `3` is `1` since `10/3` is `3` times remainder `1`, in java, `%` is the modulo operator

* read the `PRI` code.
* notice the division `/` and modulo `%` operators.
* use these intial test values: number is `97`, modulo is `10`
* work with a partner an agree on what you think this code will output

### `run`

* run the code and check the output against what you predicted (`PRI` section only for now)

### `investigate`

* try other modulo values with `97`: `9`, `12`, `2`, `5`, `3`, `1`, `0`
* predict and study the results
* try other combinations of your own so that you have a good understanding of how a modulo is calculated


---
### `modify`

> uncomment the loop `MM` section (remove `/*` and `*/`)

> you may wish to comment out the `PRI` section code

* you will have seen that the loop already displays the names but not yet the line number or pounds and pence

* insert 2 lines of code within the loop (look for the `//` comment lines as a guide)
  * first display the full amount in pence, 
  * second display the line number

> output from loop after `modify` work

```
1       Edmonds     1270
2       Sandoval        2088
..
29      Bridges     2135
30      Blaese      2293
```
---

### `make`

* amend the loop code to display pounds and pence aong with the name and line number

Make sure all numbers display correctly

> sample output from `make`

```
1       Edmonds     £ 12        70 pence
2       Sandoval        £ 20        88 pence
..
29      Bridges     £ 21        35 pence
30      Blaese      £ 22        93 pence
```

---

> `challenge` 
> * the format of the list could be improved by a blank line after every 5 result lines
> * modulo can be used to check the loop variable `i`
> * decide where to insert this code and investigate what numbers should be used in the condition to produce the blank lines

```java
// replace the 0 values to 
if (i%0 == 0) {
  System.out.println("\n");
}
```
---

  ![alt text](assets/logo.png)
  
  
