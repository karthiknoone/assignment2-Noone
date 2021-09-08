# assignment2-Noone
# Karthik Noone
## Vizag
Vizag is the **largest city** and the proposed administrative capital of the Indian state of **Andhra Pradesh**.Vizag is known as **City of destiny**.It is famous for its **Costal area and Long beach roads**.Vizag is also famous for its **Weather**.

****
## Route Map
1. Started from home reached Vizag airport.
   1. Done with security check-up and Luggage got checked and dropped.They said to collect in chicago International Airport.
   2. Got boarding pass and boarded flight.
  
2. Reached Hyderabad airport and got security check and then boarded flight to delhi.

3. Arrived to Delhi international airport after 2 hours journey and waited for 5 hours to board next flight i.e United Airlines.

4. After long layover done with security check-up,got boarding pass and boarded flight.
   1. It took 15 hours to reach destination i.e United States.
   2. Reached chicago international Airport.

5. Reached Chicago international airport done with immigration check.
   1. Collected luggage bags and waited to take domestic flight.
   2. Baggages got checked in.
   3. Meanwhile collected boarding pass and waited for 7 hours to catch domestic flight.

6. Reached kansas Airport,friend came to pick me up.
   1. After long 23 hours of journery Successfully reached Maryville.

***
- I have brought a neck pillow for travel purpose.
- I have brought the travel power adpater.
- I have brought some medicines in case of emergency during travelling

Take me to [AboutMe](AboutMe.md)

## Menu Section
This is the Menu, location and price table

| Menu          | Location	| Price        |
| ------------- | ----------| ---------    |
| Coco-cola	    | McDonalds	| $1.00        |
| Mc Chicken	| McDonalds	| $1.59        |
| Oreo Mc Furry | McDonalds	| $1.20        |
| Nuggets	    | McDonalds	| $1.60        |


---
## Pithy Quotes

As Stephen King said:

> If you don't have time to read, you don't have the time (or the tools) to write. Simple as that.

> We write to taste life twice, in the moment and in retrospect

---
## Code Fencing

*union_sets opeartion* from*Disjoint Set Union* 

> In computer science, the union_sets opeartion is used in efficient implementation for controlling of tree height.
> For union by rank, a node stores its rank, which is an upper bound for its height. When a node is initialized, its rank is set to zero. To merge trees with roots a and b,
> First compare their ranks. If the ranks are different, then the larger rank tree becomes the parent, and the ranks of a and bdo not change.
> If the ranks are the same, then either one can become the parent, but the new parent's rank is incremented by one. While the rank of a node is clearly related to its height, storing ranks is more efficient than storing heights. The height of a node can change during a Find operation, so storing ranks avoids the extra effort of keeping the height correct.

union_sets opeartion [Reference_link](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)

code for union_sets opeartion

```
void make_set(int v) {
    parent[v] = v;
    rank[v] = 0;
}

void union_sets(int a, int b) {
    a = find_set(a);
    b = find_set(b);
    if (a != b) {
        if (rank[a] < rank[b])
            swap(a, b);
        parent[b] = a;
        if (rank[a] == rank[b])
            rank[a]++;
    }
}
```

union_sets opeartion [Code_link](https://cp-algorithms.com/data_structures/disjoint_set_union.html)
