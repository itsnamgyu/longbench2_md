# Metadata

- ID: 66ece545821e116aacb1dd77
- Domain: Code Repository Understanding
- Subdomain: Code repo QA
- Difficulty: easy
- Length: short

# Question

In frontend/.env, the developer gives one Vue app API URL https://api.preatlas.dynv6.net/api and an alternative http://localhost:4001. One includes path /api/ but the other doesn't. How this works?

# Choices

- A: A. The /api/ is used as a proxy rather than router. The keyword is mutable subject to specific proxy settings, like that of nginx.
- B: B. Using a domain name and path is completely different with using IP address and port. The /api/ path is a standard for better practice and can be used out-of-the-box.
- C: C. /api/ is required for routing in this Vue project, specifically in index.js. The service at localhost:4001 somehow added the prefix /api/ during processing.
- D: D. This is a false example. Such two configurations cannot both work if we don't change other parts of the projet.

# Answer

A
