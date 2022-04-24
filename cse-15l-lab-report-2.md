# Week 4 Lab Report

[Failed Test 1](https://ejoa27.github.io/CSE15L/Test-files/brackets-test.md)

![brackets](Images/Brackets-test.png)

![CodeDiff](Images/CodeDiff.png)

The bug in this code is that it does not have any countermeasures for when the test-file does not have the correct format. As shown in the image above, the symptom in the code is that there will be a StringIndexOutOfBoundsException when the code looks for a substring because it will start from the index of the first open parenthesis, in this case the starting index being -1 since the test-file does not have any parenthesis. I solved this bug by adding an if statement in lines 20-22 that checks if an open parenthesis or close parenthesis are not found after current index, the loop should, and the list of Strings should be returned. For this input, the list returned should be empty since none of the links in the test file have the correct format.

[Failed Test 2](https://ejoa27.github.io/CSE15L/Test-files/parenthesis-test.md)

![parenthesis](Images/parenthesis-test.png)

![CodeDiff](Images/CodeDiff.png)

The bug in this code is that any test files with the incorrect format can lead to an infinite loop. In the image above, the code will continue forever, and not print anything so it can only be stopped by terminating the terminal. I added a counter that would break the loop once it went through 10 iterations for the purpose of testing what would be printed if the loop were to end.

[Failed Test 3](https://ejoa27.github.io/CSE15L/Test-files/another-test.md)

![another](Images/Another-test.png)

![CodeDiff](Images/CodeDiff.png)
