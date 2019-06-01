# Git Commit Etiquette

Using a tool frequently does not necessarily mean you know how to use that tool well.

It's time to grow up and start using git more effectively. It's what a professional programmer would do.

---

## The Commit Message Format
### The first line:
- Starts with a capital letter
- Is 50 characters or less
- Has no punctuation
- Is in the imperative voice (i.e. 'Add new About Us page' or 'Refactor tests for the Account model')
- Completes the sentence, "If accepted, this commit will **< the first line of your commit message >**."

### The second line:
- Is blank, always

### The body (everything past the second line):
- Is 72 characters or less per line
- Explains the "what" and "why" for your changes, never the "how" (that's documented in the code)
- Has blank lines separating paragraphs
- May use bullet points (typically a hyphen or asterisk followed by a single space, with blank lines in between)
- May be omitted if the change is minor and can be understood from the title alone

---

## Making Commits
- Use your terminal and an editor (stop using git commit -m "Useless message")
- Take a minute to think about the work you just did
- Write a well thought out message that follows the commit message format outlined above
- Be atomic & keep like changes together

---

### Relevant Sources
1. [A Note About Git Commit Messages][1] by Tim Pope
2. [How to Write a Git Commit Message][2] by Chris Beams
3. ["Git" it together][3] by Jeremy Gunter
3. The [Pro Git][4] book by Scott Chacon and Ben Straub

[1]:https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html
[2]:https://chris.beams.io/posts/git-commit/
[3]:https://hackernoon.com/git-it-together-some-tips-on-commit-etiquette-and-best-practices-for-junior-developers-1f147b8dfd56
[4]:https://git-scm.com/book/en/v2
