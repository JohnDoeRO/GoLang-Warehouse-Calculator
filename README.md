# GoLang-Warehouse-Calculator

*** READ THIS:
* If you have to take a test for an interview with a company whose name is almost identical to ebay
* I recommend you look elsewhere for the solution - because after I sent them my solution
* I have never heard of them :)
***

Werhouse laid out as below:
_________________________________________
|          y                            |
|   |A10|B10|   |C10|D10|   |E10|F10|   |
|   |A09|B09|   |C09|D09|   |E09|F09|   |
|   |A08|B09| x |C09|D09|   |E09|F09|   |
|   |A07|B09|   |C09|D09|   |E09|F09|   |
|   |A06|B09|   |C09|D09|   |E09|F09|   |
|   |A05|B09|   |C09|D09|   |E09|F09|   |
|   |A04|B09|   |C09|D09|   |E09|F09|   |
|   |A03|B09|   |C09|D09|   |E09|F09|   |
|   |A02|B09|   |C09|D09|   |E09|F09|   |
|   |A01|B09|   |C09|D09|   |E09|F09|   |
|    p1          p2          p3         |
-----------------------------------------

Products exist in bin locations from A1-F10
● Picking stations are marked as P1, P2 and P3
● A picker can only pick a bin from the side
    ○ A picker standing at X can pick from bins B6 and C6
    ○ A picker standing at Y cannot pick from anywhere
● A picker can walk directly through the packing stations but cannot walk through any product bins


Requirements
1. Create a database of 60 products. Assign each a stock level and a unique bin location from the range A1 - F10 (see the warehouse floor plan below).
2. Provide a tool for querying a product or a bin location. It should return the product description, bin location and current stock level.
3. Provide a tool to generate a picking route for a list of five or more products. The algorithm should consider factors such as speed, efficiency and scalability.
4. All routes should start and end at a picking station. Your algorithm may choose which ones.