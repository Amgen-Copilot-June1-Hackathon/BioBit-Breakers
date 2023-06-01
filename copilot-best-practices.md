# Best Practices for Prompt Engineering with GitHub Copilot

> Please refer to this **blog** on tips for [prompt engineering with Copilot](https://dev.to/github/a-beginners-guide-to-prompt-engineering-with-github-copilot-3ibp)
> 
> Below is the summary of this blog

Effective use of GitHub Copilot involves understanding how to craft prompts that clearly communicate your coding needs to the AI. Below are some best practices to enhance your interactions with Copilot.

## 1. Provide High-Level Context

Start with a high-level description of what you want to accomplish. This helps GitHub Copilot understand the broader context. However, keep in mind that the AI does not have a memory of past interactions. Each prompt should be self-contained and meaningful on its own.

```python
# I want to write a function that sorts a list of integers in ascending order.
```

## 2. Specify Detailed Instructions

After providing high-level context, follow up with more specific instructions. Clearly state the requirements and constraints of your problem. The more detail you provide, the better the AI can tailor its suggestions to your needs.

```python
# I want to write a function that sorts a list of integers in ascending order.
# The function should take a list as an input parameter.
# It should return a new list with the integers sorted in ascending order.
# Please do not use Python's built-in sort function.
```

## 3. Include Input and Output Examples

Providing example inputs and expected outputs can greatly improve the clarity of your prompt. This serves as a clear specification for the AI, and can help it generate more accurate code suggestions.

```python
# I want to write a function that sorts a list of integers in ascending order.
# The function should take a list as an input parameter.
# It should return a new list with the integers sorted in ascending order.
# Please do not use Python's built-in sort function.
# For example, if the input is [3, 1, 2], the output should be [1, 2, 3].
```

## 4. Iterate and Refine Your Prompts

If the initial code suggestion from GitHub Copilot isn't quite what you're looking for, don't be discouraged. Iteratively refine your prompt by providing more detail or clarity. This can lead to a better alignment between the AI's output and your requirements.

```python
# The function I want should sort a list of integers in ascending order without using built-in sort functions.
# It should use the bubble sort algorithm.
# For example, if the input is [3, 1, 2], the output should be [1, 2, 3].
```

## 5. Use Precise Naming Conventions

If your codebase has specific naming conventions for variables, functions, or other entities, incorporate them into your prompts. This helps Copilot generate code that is consistent with your existing codebase.

```python
# I want to write a function named 'sortIntegers' that sorts a list named 'inputList' of integers in ascending order.
# 'sortIntegers' should take 'inputList' as an input parameter.
# It should return a new list named 'sortedList' with the integers sorted in ascending order.
```

## 6. Promote Good Coding Practices

GitHub Copilot is a tool, not a substitute for sound programming practices. While it can generate suggestions, it's up to you to ensure that the resulting code is efficient, readable, and maintainable.

```python
# I want to write a function named 'sortIntegers' that sorts a list named 'inputList' of integers in ascending order.
# 'sortIntegers' should take 'inputList' as an input parameter.
# It should return a new list named 'sortedList' with the integers sorted in ascendingorder. Ensure the code is efficient, follows good coding practices, and includes appropriate comments for better readability.
```

## 7. Be Aware of the AI's Limitations

Remember that GitHub Copilot doesn't understand your code in the same way a human would. It doesn't know the specifics of your project or the wider context beyond the current prompt. Be prepared to review and revise the AI's suggestions to fit your specific needs.

## 8. Leverage Comments for Additional Guidance

If you're seeking to solve a more complex problem, consider breaking it down into smaller parts and using comments to guide the AI through each step. This can help you obtain more focused and manageable suggestions.

```python
# I'm building a function to perform a complex calculation. 
# First, I need to compute the sum of squares of all numbers in the input list.
# Next, I need to find the square root of that sum.
# Finally, I need to divide each number in the list by this root to normalize the list.
```

## 9. Use External Libraries

If your solution involves using specific libraries, include the import statements in your prompt. GitHub Copilot can generate code that uses those libraries.

```python
# I want to use the numpy library to perform operations on an array of integers.
# First, import the numpy library.
# Then, write a function that calculates the mean of an array using numpy's mean function.
```

> GitHub Copilot can be a powerful tool in your coding toolkit when used effectively. Remember, it is an assistant, not a replacement for your coding skills. Always review and verify the code it generates to ensure it meets your needs and adheres to best practices.

### References

- [Copilot Keyboard Shortcuts](https://docs.github.com/en/copilot/configuring-github-copilot/configuring-github-copilot-in-your-environment?tool=vscode#keyboard-shortcuts-for-macos-1)
- [VSCode shortcuts for Mac OS](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
- [VSCode shortcuts for Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)
- [Best Practices for Beginners](https://dev.to/github/a-beginners-guide-to-prompt-engineering-with-github-copilot-3ibp)
