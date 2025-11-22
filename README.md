# Graph6

🔁 Graph6 is a class with two static methods: one to convert a matrix into a text string in the .g6 format specification, and another to perform the inverse process.

💻 Initially created for use in my Computer Science undergraduate thesis ([APP here](https://total-color.vercel.app/)).

🔠 Graph6 (.g6) is a text-based format that maps undirected graph matrices to ASCII characters. Created by Brendan McKay, its specification is available at [https://users.cecs.anu.edu.au/~bdm/data/formats.txt](https://users.cecs.anu.edu.au/~bdm/data/formats.txt).


## Usage

```typescript

import Graph6 from "graph6";

// Example: To convert a matrix to graph6

const matrix = [
    [0,1,1],
    [0,0,1],
    [0,0,0],
];

const result = Graph6.parse(matrix);


// Example2: To convert graph6 to a matrix

const g6Str = "Bw";

const result2 = Graph6.toMatrix(g6Str);

```
