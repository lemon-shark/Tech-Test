### Test

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/b101ac6532624035bad423b0b3cef424)](https://app.codacy.com/manual/lemon-shark/ormuco?utm_source=github.com&utm_medium=referral&utm_content=lemon-shark/ormuco&utm_campaign=Badge_Grade_Dashboard)

>
>
> ##### Question A:
> Your goal for this question is to write a program that accepts two lines (x1,x2) and (x3,x4) on the x-axis and returns > whether they overlap. As an example, (1,5) and (2,6) overlaps but not (1,5) and (6,8).

### The Answers

#### Question A:

source directory: `./Chloe_Zhu_test/overlap.js`

usage: 

- Run `index.html`
- The project host in `https://lemon-shark.github.io/`

```
Type in 2 Points of Line 1, and 2 Points of Line 2 in the Simple web form

# It will return "Overlapping" if the lines overlap, "Not Overlapping" otherwise. If user input is 
non-numerical or empty, it will return "Invalid Input Type"
```
>
> ##### Question B:
> The goal of this question is to write a software library that accepts 2 version string as input and returns whether one is greater than, equal, or less than the other. As an example: “1.2” is greater than “1.1”. Please provide all test cases you could think of.
>

#### Question B:

source directory: `./Chloe_Zhu_test/compareVersionStrings.js`

usage: 

- Run `index.html`
- The project host in `https://lemon-shark.github.io/`
```
Type in 2 Version Strins in the Simple web form

# It will return:
#     "is larger than": If the first version is greater than the second  
#     "is less than": If the first version is smaller than the second
#     "equals": If the versions are equals
```
> ##### Question C:
> At Ormuco, we want to optimize every bits of software we write. Your goal is to write a new library that can be integrated to the Ormuco stack. Dealing with network issues everyday, latency is our biggest problem. Thus, your challenge is to write a new Geo Distributed LRU (Least Recently Used) cache with time expiration. This library will be used extensively by many of our services so it needs to meet the following criteria:
> 1. Simplicity. Integration needs to be dead simple.
> 2. Resilient to network failures or crashes.
> 3. Near real time replication of data across Geolocation. Writes need to be in real time.
> 4. Data consistency across regions
> 5. Locality of reference, data should almost always be available from the closest region
> 6. Flexible Schema
> 7. Cache can expire 
>
#### Question C:

source directory: `./Chloe_Zhu_test/LRU_Cache/cache.py`

Design and implement a data structure for Least Recently Used (LRU) cache. It should support the following operations: get and put.

get(key) - Get the value (will always be positive) of the key if the key exists in the cache, otherwise return -1.
put(key, value) - Set or insert the value if the key is not already present. When the cache reached its capacity, it should invalidate the least recently used item before inserting a new item.

The cache is initialized with a positive capacity. It runs in O(1) time complexity. 

Here is the profiling result of LRU Cache:
![Alt text](chloe_zhu_test/LRU_Cache/cache.png?raw=true "Profiling result")


