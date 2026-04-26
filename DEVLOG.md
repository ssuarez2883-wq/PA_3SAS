# DEVLOG

## Entry 1 - [4/22/26]
**Issue encountered:**  
Needed to correctly handle invalid positions in dfs - like out of bounds or hitting walls.

**Error messages or symptoms:**  
Without the proper checks, dfs could attempt to access invalid indices or attempt to move through walls.

**Attempts made:**  
looked at how 2D vectors are indexed and what are consnidered edge cases when moving in every four directions.

**Final resolution:**  
Added boundary checks and wall detection at the beginning of dfs function.

**Notes:**  
fix invalid boundaries/access points early on because it helps prevent mess-ups later when u get into the actual recursive part.

---

## Entry 2 - [4/23/26]
**Issue encountered:**  
Needed to implement how to avoid visiting already-checked cells. If not, it could cause infinite recursion.

**Error messages or symptoms:**  
Continous looping forever.

**Attempts made:**  
Recovered how arrays/2D arrays are typically used in dfs to figure out where the check should be/look like.

**Final resolution:**  
Implemented the check by seeing if visited at [r][c] is true, and if so returning false - basically telling the
program that there isn't anything to be checked/visited.

**Notes:**  
I was really confused as to whether or not return true or false for if it has been visited. After a tad bit of research
and review, I decided on false; however, i probably am gonna need to come back to this later if there are problems.

---

## Entry 3 - [4/24/26]
**Issue encountered:**  
Needed way to actually explore other cells

**Error messages or symptoms:**  
Issue of potential misidentification of certain cells

**Attempts made:**  
I used the dr and dc arrays to compute neighboring cell positions/coordinates 

**Final resolution:**  
I added a loop to examine four possible moving directions.

**Notes:**  
...

---

## Entry 4 - [4/26/26]
**Issue encountered:**  
Needed to actually start the exploring part of the maze

**Error messages or symptoms:**  
Function would never loop and just stop after checking one cell

**Attempts made:**  
Reviewed what arguments should be passed and how the return values should affect the recursive call

**Final resolution:**  
Added the recursive DFS call for valid neighbroing cells and ensured the function immediately returns true

**Notes:**  
...

---

## Entry 5 - [Date]
**Issue encountered:**  
...

**Error messages or symptoms:**  
...

**Attempts made:**  
...

**Final resolution:**  
...

**Notes:**  
...

---

## Entry 6 - [Date]
**Issue encountered:**  
...

**Error messages or symptoms:**  
...

**Attempts made:**  
...

**Final resolution:**  
...

**Notes:**  
...