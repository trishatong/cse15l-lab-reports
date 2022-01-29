# Week 4 Lab Report 2

### 3 Code Changes


![image](https://user-images.githubusercontent.com/97629354/151638959-ed73b81d-e1b7-46b0-b534-a0c8d339bc45.png)

[failure-inducing input 1](https://github.com/trishatong/markdown-parse/blob/3d74f0ba1e903a9f11ea5b636a6a7569fb643100/test-file8.md)

![error](cs202.PNG)

Our code did not account for an updated index. This resulted in an infinite while loop, causing the program to crash.

---

![image](https://user-images.githubusercontent.com/97629354/151635804-9c8c12f3-1caa-4334-8afd-52e690164e55.png)

[failure-inducing input 2](https://github.com/trishatong/markdown-parse/blob/3d74f0ba1e903a9f11ea5b636a6a7569fb643100/test-file9.md)

![error](cs195.PNG)

The index of the open bracket was greater than 0. This led to an infinite while loop, which resulted in a symptom in the form of an error.

---

![image](https://user-images.githubusercontent.com/97629354/151637861-c0e54073-bd81-4ad0-b403-f98732a47c6e.png)

[failure-inducing input 3](https://github.com/trishatong/markdown-parse/blob/3d74f0ba1e903a9f11ea5b636a6a7569fb643100/test2.md)

![image](https://user-images.githubusercontent.com/97629354/151638055-625eb76d-a29e-43d0-bfb4-0334c21ccebc.png)

The index of the exclamation point "!" was not accounted for when it occurred before an open bracket. Therefore, attempting to return multiple images in a row resulted in no output.
