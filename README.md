# Writing Good Documentation - WIP

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech folks to **copy, paste, share code.** A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and past their code to replicate and research issues. 

 - In order to create codeblocks in markdown you need to use three backticks (`)
 - Not to confused with quotation (')

```
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"

```

- When you can, you should apply syntax highlighting to your codeblock:

```ruby
def factorial(n)
  if n == 0
    return 1
  else
    return n * factorial(n - 1)
  end
end

# Test the factorial function
number = 5
result = factorial(number)
puts "The factorial of #{number} is #{result}"
```

Good Cloud Engineers us codeblocks for both code and Errors that appear in the console.

```bash
Traceback (most recent call last):
  File "<stdin>", line 2, in <module>
  File "<stdin>", line 2, in bar
  File "<stdin>", line 2, in foo
ZeroDivisionError: division by zero
```
> Here is an example of using a codeblock for an error that appears in bash.

# Step 2 - Use an Image:

GitHub allows you to add images to your project. `<img src="PASTE_YOUR_IMAGE_PATH_OR_URL_HERE" />`

_DevOps Infinity Loop Image_:

<img src="https://github.com/zawscloud/github-docs-example/assets/83472934/1f641097-64e6-410a-871b-5e3f3dd03a39" />

# Step 3 - Use GitHub Flavored Markdown List
GitHub extends Markdown to have a list where you can check off items.
- [x] Finish Step 1
- [ ] Finish Step 2
- [ ] Finish Step 3

# Step 4 - Use Emoji in a Table (Optional)
GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:
| ico      | shortcode |
| -------- | ------- |
| :cloud:  | `:cloud:` |
| :penguin: | `:penguin:`|
| :moneybag:| `:moneybag:`|


# Step 5 - 

## References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [GitHub emoji-cheat-sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)
