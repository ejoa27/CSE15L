# Lab Report 5

**[Link to my markdown-parse repository](https://github.com/ejoa27/markdown-parser)**

**[Link to the reviewed markdown-parse implementation](https://github.com/FishInAZ/makrdown-parse-own)**

# How did you find the tests with different results?

I found tests with different results using vimdiff after create two different results text file for the two different implementations of markdown-parse.

# Links to the test-file with different results

[22.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/22.md)

[201.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md)


# Describe which implementation is correct, or neither if both give the wrong output
Indicate both actual outputs (provide screenshots) and also what the expected output is (list the links that are expected in the output).

The left side is Lab 9's implementation's output, and the right side is mine:

Test file 22.md:

Both of our outpus are not correct for test-file 22.md since the link leads to "bar*":

![22](Images/22.png)

Test file 201.md:

For test-file 201.md, my output was correct since 201.md does not have any links:

![201](Images/201.png)

Correct outputs:

Test file 22.md:

![22Preview](Images/22Preview.png)

Test file 201.md:

![201Preview](Images/201Preview.png)

