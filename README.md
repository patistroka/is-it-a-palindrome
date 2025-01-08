# Palindrome Checker  

This is a simple Palindrome Checker app built with JavaScript and styled using CSS Flexbox. It allows users to input text and verifies if it is a palindrome, ignoring punctuation, case, and spacing.  

## Features  
- **Input Validation**: Ensures the user provides a value before checking.  
- **Palindrome Detection**: Removes non-alphanumeric characters, normalizes case, and checks if the input reads the same forward and backward.  
- **Dynamic Feedback**: Displays results directly on the page, such as whether the input is a palindrome or not.  
- **Responsive Design**: Styled with CSS Flexbox for clean and adaptable layout.  

## User Stories  
1. An input element (`id="text-input"`) to type the text to check.  
2. A button (`id="check-btn"`) to trigger the palindrome check.  
3. A result display area (`id="result"`) to show the output.  
4. Alerts the user if no input is provided.  
5. Handles various cases, such as alphanumeric strings, punctuation, and mixed case.  

### Examples:  
- Input: `race car` → Output: `"race car is a palindrome"`  
- Input: `not a palindrome` → Output: `"not a palindrome is not a palindrome"`  
- Input: `A man, a plan, a canal. Panama` → Output: `"A man, a plan, a canal. Panama is a palindrome"`  

## Technologies Used  
- **JavaScript**: Handles logic for palindrome validation and user interaction.  
- **CSS Flexbox**: Ensures a responsive and organized layout.  
- **HTML**: Structure for input, button, and result display.  

