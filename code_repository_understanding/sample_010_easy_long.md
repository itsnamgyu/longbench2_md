# Metadata

- ID: 66ec56dd821e116aacb1cd0e
- Domain: Code Repository Understanding
- Subdomain: Code repo QA
- Difficulty: easy
- Length: long

# Question

I want to extend the task of Agentbench. My task is a mobile operation task, implemented using an Android virtual device. When setting up this task, it is necessary to consider that each AVD occupies a large amount of memory and needs to control the concurrency based on the remaining memory of the machine; And AVD needs to be restarted after each test case to prevent mutual influence between tasks. Which of the following operations have errors:

# Choices

- A: Inherit the Task class and change self.name to my task name
- B: When the start_stample function starts executing, consider the system memory situation and only start the test when there is sufficient remaining memory, otherwise wait
- C: Exit AVD in the release function and end testing Docker
- D: Calculate each test result in calculate_overall and return the result in JSON format

# Answer

C
