# Writing Good Documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code. A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows them to copy and paste their code to replicate or research issues.

- In order to create code blocks in markdown you need to use three backticks ```

```
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"

```
- When you can you should attempt to apply syntax highlighting to your code blocks

```ruby
def factorial(n)
  if n <= 1
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Calculate the factorial of 5
result = factorial(5)
puts "Factorial of 5 is #{result}"
```

![hardworkiskeytosuccess](https://github.com/cammyong/github-docs-example/assets/34858886/e99caeb3-9613-4ded-a0ce-a1f9ab0158fc)


> Here is an example of using a code block for an error that appears in bash

```
# This code attempts to access an undefined variable 'undefined_variable'
puts undefined_variable
```

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items.[<sup>[1]<sup>](#external-references)

- [x] Finish Step 1
- [] Finish Step 2
- [] Finish Step 3

# Step 4 - Use Emojis (Optional)
GitHub Flavored Markdown (GFM) supports emojis shortcodes.
Here are some examples:

| Name | Shortcode | Emoji
| --- | --- | --- |
| Cloud | `:cloud:`| :cloud: |
| Cloud with lighting| `:cloud_with_lighting` | 🌩️ |

# Step 5  - How to create a table

You can use the following markdown format to create tables:
```md
| Name | Shortcode | Emoji
| --- | --- | --- |
| Cloud | `:cloud:`| :cloud: |
| Cloud with lighting| `:cloud_with_lighting` | 🌩️ |
```
Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[3]<sup>](#external-references)

## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) <sup>[1]<sup>
- [Basic writing and formatting syntax (GitHub Flavored Markdown Spec)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>[2]<sup>
- [GFM - Tasks Lists](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists)
- [GTM - Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (With Extension)](https://github.github.com/gfm/#tables-extension-)<sup>[3]<sup>
