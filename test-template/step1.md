
Clone the following github repository.

`git clone https://github.com/polyu18046521d/wordpress-shop`{{execute}}
## Lesson Content

View the docker compose file at wordpress-shop/docker-compose.yml in the editor
### Description

Open with a brief description: 2-3 sentences on what the lesson covers, illustrates, and teaches. What technology is used, and what task will the learner have accomplished by the end?

Importantly, why does this matter? What can this technology, tool, or approach help you accomplish? Briefly communicate the real-world application(s) of this skill.

### Learning Objective

- Include 2-4 bullets
- of what the learner
- will accomplish and learn.

### Prerequisite Skills

Who is this for? Describe the intended audience here, and list any prerequisite skills. For example: _This is for software developers with prior experience using Jenkins to deploy web applications._



## Lesson Syntax

This section describes how to use special Markdown features within lessons.

### Basic Markdown

This is a regular paragraph of text, with no special formatting.

Use single underscores or asterisks to _italicize_.

```
Use single underscores or asterisks to _italicize_.
Use single underscores or asterisks to *italicize*.
```

Use double underscores or asterisks to __embolden__.

```
Use double underscores or asterisks to __embolden__.
Use double underscores or asterisks to **embolden**.
```

[...other formatting features...]

Use single backticks to indicate `code` inline.

```
Use single backticks to indicate `code` inline.
```

Use three backticks to indicate a multiline code block.

```
cat file.txt
echo 'I did it!'
```

<pre>
```
cat file.txt
echo 'I did it!'
```
</pre>

### Make code clickable.

Make code clickable by telling markdown that the code block is a bash script. This must be a multiline code block, and the opening backticks should be followed immediately with "bash". Clicking it will then execute that code in the terminal, just as if the learner had copy/pasted it or typed it in themselves.

<pre>
```bash
echo "file contents" > file.txt
cat file.txt
```
</pre>

Try clicking this:

```bash
echo "file contents" > file.txt
cat file.txt
```


**How you could use this:** Teach the learner a new command for installing a unix package that they'll need later. Clicking the code block saves them some typing:

```bash
apt-get update
apt-get install -yy cowsay && \
/usr/games/cowthink "EAT MORE CHICKEN"




# NOTES BELOW THIS POINT

Here's a single line of runnable code:



Start up the servers by using docker-compose:
Execute:  `cd wordpress-shop`{{execute}}









