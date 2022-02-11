# Week 4 Lab Report 2

### 3 Code Changes


![image](cs287.PNG)

[failure-inducing input 1](https://github.com/trishatong/markdown-parse/blob/3d74f0ba1e903a9f11ea5b636a6a7569fb643100/test-file8.md)

![error](cs286.PNG)

Our code did not account for an open bracket whose index was not at the beginning. This caused the while loop to be infinite.

---

![image](https://user-images.githubusercontent.com/97629354/151635804-9c8c12f3-1caa-4334-8afd-52e690164e55.png)

[failure-inducing input 2](https://github.com/trishatong/markdown-parse/blob/3d74f0ba1e903a9f11ea5b636a6a7569fb643100/test-file9.md)

![error](cs195.PNG)

Our code did not account for multiple pairs of brackets and parenthesis and unpaired brackets and parenthesis. Therefore, the open bracket at the end of this file caused an error in the form of an infinite while loop.

---

![image](https://user-images.githubusercontent.com/97629354/151637861-c0e54073-bd81-4ad0-b403-f98732a47c6e.png)

[failure-inducing input 3](https://github.com/trishatong/markdown-parse/blob/3d74f0ba1e903a9f11ea5b636a6a7569fb643100/test2.md)

![image](https://user-images.githubusercontent.com/97629354/151638055-625eb76d-a29e-43d0-bfb4-0334c21ccebc.png)

The index of the exclamation point "!" was not accounted for when it occurred before an open bracket. Therefore, attempting to return multiple images in a row resulted in no output.
