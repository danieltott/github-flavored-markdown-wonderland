# Text Formatting

## General formatting

There’s only one thing I hate more than lying: _skim milk_. Which is water that’s lying about being milk. The less I know about other people’s affairs, **the happier I am**. I’m not interested in caring about people.

> I once worked with a guy for three years and never learned his name. _Best friend I ever had_.

We still never talk sometimes. Dear frozen yogurt, you are the celery of desserts. Be ice cream, or be nothing<sup>TM</sup>.

## Unordered list (`<ul>`)

###### Markdown code:

```md
- Problem Solving
- Continuous Learning
- Creativity
  - Endless possibilities with code
  - Turning ideas into reality
  - Finding elegant solutions
- Community Support
- Versatility
```

###### Rendered example:

- Problem Solving
- Continuous Learning
- Creativity
  - Endless possibilities with code
  - Turning ideas into reality
  - Finding elegant solutions
- Community Support
- Versatility

### To add block-level items inside a list item, indent the entire block-level item to the same level

###### Markdown code:

````md
- Problem Solving
- Continuous Learning
- Creativity
  - Endless possibilities with code
  - Turning ideas into reality
  - Finding elegant solutions
    ```
    if ((n & -n) == n) {
      // n is a power of two
    }
    ```
  - Another thing
- Community Support
- Versatility
````

###### Rendered example:

- Problem Solving
- Continuous Learning
- Creativity
  - Endless possibilities with code
  - Turning ideas into reality
  - Finding elegant solutions
    ```
    if ((n & -n) == n) {
      // n is a power of two
    }
    ```
  - Another thing
- Community Support
- Versatility

## Ordered list (`<ol>`)

###### Markdown code:

```md
_Top 10 Reasons Why My Code Isn't Working_

1. Named my variables after breeds of dogs. Now my code thinks it's at a dog show.
2. Accidentally threw a stick into my loops. Now my code won't stop fetching.
3. Tried to teach my code a new trick. It rolled over and played dead instead.
4. Used a leash instead of a pointer. Now my code's running in circles.
5. My code's so confused, it's chasing its own tail.
6. Accidentally gave my code a bone. Now it's buried deep in my functions.
7. Imported a library. Now my code wants to go for a walk.
8. Asked my code to speak. It just barked at me.
9. Put my code in a crate for timeout. Now it's howling for help.
10. Used copy-paste. Now my code thinks it's a clone army.
```

###### Rendered example:

_Top 10 Reasons Why My Code Isn't Working_

1. Named my variables after breeds of dogs. Now my code thinks it's at a dog show.
2. Accidentally threw a stick into my loops. Now my code won't stop fetching.
3. Tried to teach my code a new trick. It rolled over and played dead instead.
4. Used a leash instead of a pointer. Now my code's running in circles.
5. My code's so confused, it's chasing its own tail.
6. Accidentally gave my code a bone. Now it's buried deep in my functions.
7. Imported a library. Now my code wants to go for a walk.
8. Asked my code to speak. It just barked at me.
9. Put my code in a crate for timeout. Now it's howling for help.
10. Used copy-paste. Now my code thinks it's a clone army.

### Only the first number matters. Change it to start the list at a different number

###### Markdown code:

```md
1. First item
2. Second item
3. Third item
```

1. First item
2. Second item
3. Third item

###### Rendered example:

#### Starting with 7:

###### Markdown code:

```md
7. Seven things
8. Eight things
9. Nine things
```

###### Rendered example:

7. Seven things
8. Eight things
9. Nine things

## Definition List

###### Markdown code:

```md
_Reasons Why Debugging Feels Like Walking a Dog_

<dl>
  <dt>Endless Loops:</dt>
  <dd>It's like your dog chasing its tail, round and round we go.</dd>
  <dt>Mixed Messages:</dt>
  <dd>Giving commands but getting barks in response, confusing much?</dd>
  <dt>Lost in the Woods:</dt>
  <dd>Your code wanders off the path and suddenly you're in the wilderness.</dd>
  <dt>Follow the Scent:</dt>
  <dd>Tracing through code, following the scent of bugs.</dd>
  <dt>Surprise "Gifts":</dt>
  <dd>Unexpected outputs, just like surprises left on your carpet.</dd>
  <dt>Puppy Training:</dt>
  <dd>Teaching new code to behave, sit, and stay.</dd>
  <dt>Fetch Failures:</dt>
  <dd>Sending your code to fetch, but it comes back empty-pawed.</dd>
  <dt>Leash Limitations:</dt>
  <dd>Constraints that make your code feel like it's on a short leash.</dd>
  <dt>Clean-Up Duty:</dt>
  <dd>Picking up after your code's messes, memory leaks, and all.</dd>
  <dt>Unruly Behavior:</dt>
  <dd>Your code jumping on strangers, like crashing unexpectedly.</dd>
</dl>
```

###### Rendered example:

_Reasons Why Debugging Feels Like Walking a Dog_

<dl>
  <dt>Endless Loops:</dt>
  <dd>It's like your dog chasing its tail, round and round we go.</dd>
  <dt>Mixed Messages:</dt>
  <dd>Giving commands but getting barks in response, confusing much?</dd>
  <dt>Lost in the Woods:</dt>
  <dd>Your code wanders off the path and suddenly you're in the wilderness.</dd>
  <dt>Follow the Scent:</dt>
  <dd>Tracing through code, following the scent of bugs.</dd>
  <dt>Surprise "Gifts":</dt>
  <dd>Unexpected outputs, just like surprises left on your carpet.</dd>
  <dt>Puppy Training:</dt>
  <dd>Teaching new code to behave, sit, and stay.</dd>
  <dt>Fetch Failures:</dt>
  <dd>Sending your code to fetch, but it comes back empty-pawed.</dd>
  <dt>Leash Limitations:</dt>
  <dd>Constraints that make your code feel like it's on a short leash.</dd>
  <dt>Clean-Up Duty:</dt>
  <dd>Picking up after your code's messes, memory leaks, and all.</dd>
  <dt>Unruly Behavior:</dt>
  <dd>Your code jumping on strangers, like crashing unexpectedly.</dd>
</dl>

## Task Lists

###### Markdown code:

```md
- [ ] **Fix that one bug that only happens on Fridays.** It's like the code knows it's the end of the week.
- [ ] **Figure out why the code works on your machine but not on production.** Maybe the production server has stage fright.
- [ ] **Refactor spaghetti code into linguini code.** Because life's too short for tangled noodles.
- [ ] **Attend yet another meeting about meetings.** Because talking about talking is the best use of our time.
- [ ] **Explain to your non-tech friends what you do for a living.** "So, you just type on a computer all day?"
- [ ] **Google an error message and immediately feel like an imposter.** "I've been coding for years, but what is this?"
- [ ] **Accidentally commit sensitive information and hope no one notices.** Git blame? More like git shame.
- [ ] **Resist the urge to rewrite the entire project in [insert trendy new language/framework here].** But it would be so much cooler in Rust.js, right?
- [ ] **Try to remember why you chose this career in the first place.** Oh right, because you love staring at a screen for 8+ hours a day.
- [ ] **Celebrate fixing a bug with a victory dance.** Because every squashed bug deserves a party.
```

###### Rendered example:

- [ ] **Fix that one bug that only happens on Fridays.** It's like the code knows it's the end of the week.
- [ ] **Figure out why the code works on your machine but not on production.** Maybe the production server has stage fright.
- [ ] **Refactor spaghetti code into linguini code.** Because life's too short for tangled noodles.
- [ ] **Attend yet another meeting about meetings.** Because talking about talking is the best use of our time.
- [ ] **Explain to your non-tech friends what you do for a living.** "So, you just type on a computer all day?"
- [ ] **Google an error message and immediately feel like an imposter.** "I've been coding for years, but what is this?"
- [ ] **Accidentally commit sensitive information and hope no one notices.** Git blame? More like git shame.
- [ ] **Resist the urge to rewrite the entire project in [insert trendy new language/framework here].** But it would be so much cooler in Rust.js, right?
- [ ] **Try to remember why you chose this career in the first place.** Oh right, because you love staring at a screen for 8+ hours a day.
- [ ] **Celebrate fixing a bug with a victory dance.** Because every squashed bug deserves a party.

## Collapsed sections

###### Markdown code:

````

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

Just make sure there is a full line break between the `</summary>` tag and your markdown.

You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby
   puts "Hello World"
````

</details>
````

###### Rendered example:

<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

Just make sure there is a full line break between the `</summary>` tag and your markdown.

You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>

## Links

###### Markdown code:

```md
- https://virtualcoffee.io
- [VirtualCoffeeIO](https://virtualcoffee.io)
- [Relative link](img/bugs-2.jpg)
- #1
- https://github.com/Virtual-Coffee/virtualcoffee.io/issues/13
- Virtual-Coffee/virtualcoffee.io#13
- Linking to lines of code on github:
  - Single line:
    https://github.com/danieltott/github-flavored-markdown-wonderland/blob/ae4e1524ed0fd15ab3d861a5137cb723c917ed0c/README.md?plain=1#L6
  - Multiple lines:
    https://github.com/danieltott/github-flavored-markdown-wonderland/blob/ae4e1524ed0fd15ab3d861a5137cb723c917ed0c/README.md?plain=1#L8-L14
```

###### Rendered example:

- https://virtualcoffee.io
- [VirtualCoffeeIO](https://virtualcoffee.io)
- [Relative link](img/bugs-2.jpg)
- #1
- https://github.com/Virtual-Coffee/virtualcoffee.io/issues/13
- Virtual-Coffee/virtualcoffee.io#13
- Linking to lines of code on github:
  - Single line:
    https://github.com/danieltott/github-flavored-markdown-wonderland/blob/ae4e1524ed0fd15ab3d861a5137cb723c917ed0c/README.md?plain=1#L6
  - Multiple lines:
    https://github.com/danieltott/github-flavored-markdown-wonderland/blob/ae4e1524ed0fd15ab3d861a5137cb723c917ed0c/README.md?plain=1#L8-L14

## Previewing Colors

###### Markdown code:

```md
I was thinking about using `#006699` for the header and `#ff0000` for the footer, what do you think?
```

###### Rendered example:

I was thinking about using `#006699` for the header and `#ff0000` for the footer, what do you think?

## Footnotes

###### Markdown code:

```md
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]:
    To add line breaks within a footnote, prefix new lines with 2 spaces.
    This is a second line.

The footnotes do not have to be at the bottom of the content - but they will always appear there[^3]

[^3]: See?
```

###### Rendered example:

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]:
    To add line breaks within a footnote, prefix new lines with 2 spaces.
    This is a second line.

The footnotes do not have to be at the bottom of the content - but they will always appear there[^3]

[^3]: See?

## Alerts!

###### Markdown code:

```md
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```

###### Rendered example:

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
