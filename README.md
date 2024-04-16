
## Working with Git
Learning Git has been interesting. I'm grateful to this resource [Git Minesweeper](https://profy.dev/project/github-minesweeper#start-project) that has helped me navigate my way around using Git in a fun and practical way.

### Git Commands
Below are some of the Git commands I have learnt so far and what they do.

| Command         | Description                                                                                        |
| -----------     | -----------                                                                                        |
| git branch      | Shows all the existing branches in the repository and highlights the current branch in color       |
| git checkout    | Switch to a new or existing branch                                                                 |
| git add         | Stages all changes made to a file or files                                                         |
| git commit      | Commits all changes made with a commit hash                                                        |
| git log         | Logs changes made by displaying the name of the commit and who made the commit                     |

### Collaborate on a Git repository
To work with collaborators on a Git repository in GitHub, it's important to do the following in this order:
1. Clone the existing GitHub repository to your local computer
2. Open the repository in your preferred IDE
3. It is not ideal to make changes directly to the main/master branch. So create a new branch and switch to it
4. Make changes to the necessary files in the repository
5. Commit the changes
6. Push the changes to the remote repository on GitHub
7. Create a pull request and ask for review from a senior engineer

### Things to Note
- You should always create a new branch from the main/master branch
- When you create a pull request and your work is approved and merged to the main branch, to continue working on your local computer, **ensure to switch to the main branch first and pull changes**. you can then create another branch from the main branch.

### Extra

Here is how to use equation in Markdown:

To add a math expression as a block, start a new line and *delimit* the expression with two dollar symbols `$$`

**The Cauchy-Schwarz Inequality**

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

Here's how to use inline code in Markdown:

If  `x = 3`, that means `x + 2 = 5`

Here's how to use a code block in Markdown,

You can add an ***optional language identifier*** to enable syntax highlighting in your fenced code block. Syntax highlighting changes the color and style of source code to make it easier to read. For example, to syntax highlight JavaScript code

```javascript
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```