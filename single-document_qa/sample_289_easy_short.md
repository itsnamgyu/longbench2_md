# Metadata

- ID: 66ec1de5821e116aacb1adca
- Domain: Single-Document QA
- Subdomain: Academic
- Difficulty: easy
- Length: short

# Question

How does the MagicDrive encode the bounding box in training step?

# Choices

- A: MagicDrive encode the class labels of bounding box by the method similar to Li et al, where the pooled embeddings of the class names are considered as the label embeddings. And then uses an MLP to compress both the class and text embeddings into a single hidden vector for each bounding box.
- B: MagicDrive uses Fourier embedding for 4 corner point and passes them through an MLP for encoding in training step. MagicDrive then uses an MLP to compress both the class label and position embeddings into a single hidden vector for each bounding box.
- C: MagicDrive using the text encoder to encode the class label of bounding box,  and then uses an MLP to compress both the class and text embeddings into a single hidden vector for each bounding box.
- D: MagicDrive encode the class labels and the corner points separately, and then uses an MLP to compress them into a vector.

# Answer

D
