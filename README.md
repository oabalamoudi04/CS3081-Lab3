# CS3081-Lab3
##Name: Ohoud Alamoudi 
##Student Id: S24109009
----------------------------------

# Part 1 – Search (BFS)

## Exercise 1 – Change the Goal City

I changed the goal city from `Dammam` to `Madinah` and ran the BFS program again.

### Answers
**a. How many steps did BFS take to reach Madinah?**  
BFS took **4 steps** to reach Madinah.

**b. What is the path it found?**  
The path found was:  
`Makkah -> Jeddah -> Madinah`

**c. Is this the shortest path?**  
Yes, this is the shortest path because BFS explores level by level and always finds the path with the fewest hops.

### Screenshot
<!-- Add screenshot for Exercise 1 here -->
![Exercise 1 Output](screenshots/ex1-part1.png)

---

## Exercise 2 – Add a New City

I added a new city called `Abha` to the map and connected it to `Taif`. Then I changed the goal city to `Abha` and ran the program.

### Answer
The path BFS found from Makkah to Abha was:  
`Makkah -> Taif -> Abha`

This is the correct shortest path after adding the new city.

### Screenshot

![Exercise 2 Output](p1_2.png)

---

# Part 2 – Knowledge Base

## Exercise 3 – Add a New Clue

I added the clue that **Nora has a key** by adding:

```python
nora_key = Symbol("NoraHasKey")
kb.tell(nora_key)
