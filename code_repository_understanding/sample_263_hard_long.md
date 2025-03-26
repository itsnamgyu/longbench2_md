# Metadata

- ID: 66f3fd3a821e116aacb30533
- Domain: Code Repository Understanding
- Subdomain: Code repo QA
- Difficulty: hard
- Length: long

# Question

If I want to create a subfolder for each user under the "input" folder and place the images uploaded by different users into their respective folders as input, how should I write http request? (Including Request URL, Request Method, Content-type and Params (Regardless of the format, just give the key-value). Suppose the image need to be upload is given and named "file" and subfolder want to be named "username")

# Choices

- A: Url: /upload/image
Method:post 
Content-Type:application/json
Parameters: 
{
file:file,
folder:"input",
subfolder:username,
}
- B: Url: /upload/image
Method:post 
Content-Type:multipart/form-data
Parameters: 
{
image:file,
type:"input",
subfolder:username,
}
- C: Url: /upload/image
Method:post 
Content-Type:application/json
Parameters: 
{
image:file,
type:"input",
subfolder:username,
}
- D: Url: /upload/image
Method:post 
Content-Type:multipart/form-data
Parameters: 
{
file:file,
folder:"input",
subfolder:username,
}

# Answer

B
