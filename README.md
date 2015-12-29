# FreeCodeCamp

function palindrome(str) {
  var lowercasePalindrome = str.toLowerCase(); 
  /*Makes the inputted string lowercase*/
  var PalindromewithNoSpaces = lowercasePalindrome.replace(/\s/g, '');
  
  var newStr = lowercasePalindrome.replace(/\s/g, '');
  /*Sets newStr variable as the lowercased no spaces (inputted) string */
  
  
  
 
  if (PalindromewithNoSpaces === newStr) {
    return true;
  }
  
  else if (PalindromewithNoSpaces !== newStr) {
    return false;
  }
  
}

palindrome("nope");


