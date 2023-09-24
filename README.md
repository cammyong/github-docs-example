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

## References

-  [GitHub Flavored Markdown Spec] (https://github.github.com/gfm/)
- [Basic writing and formatting syntax (GitHub Flavored Markdown Spec)] (https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
