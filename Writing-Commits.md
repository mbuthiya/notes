## Writing a proper commit 
*The seven Holy rules*

1. Separate the subject from body with a blank space
---
        Separating the subject line and body is useful when viewing git logs for your project

        It makes the git logs more user friendly to read and provided quick needed information

        Commands: ```git log --oneline ``` prints out the subject line ```git shortlog``` groups commits by user and subject is the only thing printed.

2. Limit the subject line to 50 characters
---

        The subject line should be short and precise. It makes sure the commits are readable.


3. Capitalize the subject line
---
        Start the subject line with a capital letter

4. Do not end the subject line with a period

5. Use imparative mood for the subject line
---
        Imparative mood means spoken or written as giving a command

        ie :
        ```Update ReadMe```
        ```Create new HTML file```
        ```Fix the downtime file```

        A properly formatted git commit subject line should finish this sentence

        *If applied this commit will...*

6. Wrap the body at 72 characters long
---
        Total maximum length of the body should be 72 characters per line.

7. Use body to explain the what and why vs how

        Explain why you made the change in the first place. How things were working before and how things are working now and why you have decided to solve it that way

[Read More on the the official blog](https://chris.beams.io/posts/git-commit/)



