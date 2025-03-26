# Metadata

- ID: 66f3c219821e116aacb2eb4e
- Domain: Code Repository Understanding
- Subdomain: Code repo QA
- Difficulty: hard
- Length: medium

# Question

I want to run this test in parallel on a Linux (x86-64) environment, but unfortunately, port 6060 on my host is already occupied. How to adjust this code to run correctly?

# Choices

- A: Use the methods and images in the documents/Prepare AVD on Mac to migrate to my environment and run it.
- B: Replace the docker_port of the docker run - idd -- privileged - p {docker-local_port}: {docker_port} {docker_image_name} instruction with an available port in evaluation/docker_utils_py.
- C: Replace line 121 start_port=6060 with an available port in evaluation/auto_test.py.
- D: Modify the port to an available port in the test YAML file.

# Answer

C
