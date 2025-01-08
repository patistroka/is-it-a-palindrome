//DOM elements
const textInput = document.getElementById("text-input");
const checkBtn = document.getElementById("check-btn");
const result = document.getElementById("result");

//eventListener to button
checkBtn.addEventListener("click", () => {
  const inputValue = textInput.value.trim();

  if(!inputValue) {
    alert("Please input a value");
    return;
  }
  checkPalindrome(inputValue);
});

//logic / function
function checkPalindrome(input) {
  const originalText = input;
  const cleanedText = input.replace(/[^a-zA-Z0-9]/g, "").toLowerCase();
  const isPalindrome = cleanedText === cleanedText.split("").reverse().join("");

  if (isPalindrome) {
    result.textContent = `${originalText} Is a palindrome`;
  } else {
    result.textContent = `${originalText} Is not a palindrome`;
  }
}
