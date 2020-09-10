# reading-notes
## These are my reading notes


## Growth mindset is accomplishing short term goals for long term progress!
- Dive in and *just keep swimming*
- Making an effort; a partially constructed bridge would be a nightmare
- Using the community or class to inspire and learn

### My ~~name~~ is Ricardo. I was sick of living in deserts, so my partner and I moved to the Seattle area knowing only each other here. I enjoy learning new things, playing sports and building things.   [GitHub](https://github.com/ZenAtomsk)


# These are my reading notes

## Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform.
- Markdown is a way to style text on the web to control the display of the document; formatting words as bold or italic, adding images, and creating lists.
- Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *

## Examples: 

### Text: It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)

### Lists: Sometimes you want numbered lists:

1. One
2. Two
3. Three

Sometimes you want bullet points:

* Start a line with a star
* Profit!

Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
  
Images: If you want to embed images, this is how you do it:
  
  -exclamation symbol[title] followed by the link in parenthases
  
![Image of Yaktocat](image of an awesome cat thing) (this image is broken on purpose, the cat picture was huuuuuge)

### Headers and quotes: # Structured documents

Sometimes it's useful to have different levels of headings to structure your documents. Start lines with a `#` to create headings. Multiple `##` in a row denote smaller heading sizes.

#### This is a fourth-tier heading
##### This is a fifth-tier heading

You can use one `#` all the way up to `######` six for different heading sizes.

If you'd like to quote someone, use the > character before the line:

> Coffee. The finest organic suspension ever devised... I beat the Borg with it.
> - Captain Janeway

## Code: There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: ` var example = true `.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```

## Extras: GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ]  This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji!

## Markdown syntax can be searched in search engines for shortcuts or cheet sheets.

## GitHub.com uses its own version of the Markdown syntax that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

## Types of syntax
- headers
- emphasis
- lists (unordered/ordered)
- images
- links
- blockquotes
- inline code

## GitHub uses its own version of Markdown syntax for additional features

1.**Syntax highlighting**
  - you can also indent your code by four spaces

2.**Task Lists**
    - [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
    - [x] list syntax required (any unordered or ordered list supported)
    - [x] this is a complete item
    - [ ] this is an incomplete item
- **if you include a task list in the first comment of an issue, you will get a progress indicator in you issue list**3. 

3.**Tables**
- you can creat tables by assembling a list of words and dividing them with hypens - (for the first row), and then separating each column with a pipe | :

**Year** | **Number of succesfull graduates**
------------ | -------------
1908 | 2
2020 | 200

4.**SHA references** (is a cryptographic hash function which takes an input and produces a 160-bit (20-byte) hash value known as a message digest – typically rendered as a hexadecimal number, 40 digits long)
- any reference to a commit's SHA-1 hash will be automatically converted into a link to that commit on GitHub.

16c999e8c71134401a78d4d46435517b2271d6ac
mojombo@16c999e8c71134401a78d4d46435517b2271d6ac
mojombo/github-flavored-markdown@16c999e8c71134401a78d4d46435517b2271d6ac

5.**Issue references within a repository**
- Any number that refers to an Issue or Pull Request will be automatically converted into a link.

#1
mojombo#1
mojombo/github-flavored-markdown#1

6.**Username @mentions**
- Typing an @ symbol, followed by a username, will notify that person to come and view the comment. This is called an “@mention”, because you’re mentioning the individual. You can also @mention teams within an organization.

7.**Automatic linking for URLs** 
- Any URL (like http://www.github.com/) will be automatically converted into a clickable link.
- you can also use [] to title your link, making it clickable with the link directly after using ()

8.**Strikethrough**
- any word wrapped with two tildes ~~experience~~ will be crossed out
- ~~any word wrapped with two tildes will be crossed out~~

9.**Emoji**
- Github supports emoji.
You can add emoji to your writing by typing :EMOJICODE:.
@octocat :+1: This PR looks great - it's ready to merge! :shipit:



Also great document for more reading https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#using-emoji
[Awesome Document](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax#using-emoji)



# reading notes	part 2
## these are my reading notes.
## Introduction The command line!
(Linux has a graphical user interface that works like GUI.)
focus instead on the command line (also known as a terminal) running Bash.
The command line looks daunting.you can have several command lines open and doing different tasks in each at the same time. 
## What are they?
A command line, or terminal, is a text based interface to the system. you are able to enter commands by typing them on the keyboard
and feedback will be given to you similarly as text.
The command line typically presents you with a prompt. As you type, it will be displayed after the prompt.
Most of the time you will be issuing commands. Here is an example:

| terminal | Example |
| ----- | ----- |
| 1. | user@bash: ls -1 /home/ryan |
| 2. | total 3 |
| 3. | drwxr-xr-x 2 ryan users 4096 Mar 23 13:34 bin |
| 4. | drwxr-xr-x 18 ryan users 4096 Feb 17 09:12 Documents |
| 5. | drwxr-xr-x 2 ryan users 4096 May 05 17:25 public_html |
| 6. | user@bash: |

- **Line 1** presents us with a prompt ( user@bash ). After that we entered a command ( ls ). Typically a command is always the first 
thing you type. After that we have what are referred to as command line arguments ( -l /home/ryan ). Important to note, these are 
separated by spaces (there must be a space between the command and the first command line argument also). The first 
command line argument ( -l ) is also referred to as an option. Options are typically used to modify the behaviour of the command. 
Options are usually listed before other arguments and typically start with a dash ( - ).
- **Lines 2 - 5** are output from running the command. Most commands produce output and it will be listed straight under the issuing 
of the command. Other commands just perform their task and don't display any information unless there was an error.
- **Line 6** presents us with a prompt again. After the command has run and the terminal is ready for you to enter another command 
the prompt will be displayed. If no prompt is displayed then the command may still be running (you will learn later how to deal with 
this).
Your terminal probably won't have line numbers on it. I have just included them here to make it easier to refer to different parts of 
the material
