To find the tests with different results, I used diff: `diff markdown-parse/results.txt lab9/markdown-parse/results.txt`

**Test 1**:
`[link](/url "title "and" title")`

My implementation:

![mine-test1](cs449.PNG)

 What's wrong: Needs to account for ](/ in a row
 
 ![mine-test1](cs453.PNG)

Provided implementation:

![provided-test1](cs450.PNG)

Expected output: [link](/url "title "and" title")

---

**Test 2**:
`[link](/my uri)`

My implementation:

![mine-test1](cs451.PNG)

What's wrong: Needs to account for ](/ in a row

![mine-test1](cs453.PNG)

Provided implementation:

![provided-test1](cs452.PNG)

Expected output: [link](/my uri)
