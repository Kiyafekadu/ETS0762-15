# .isdigit() string method

The python '.isdigit()' funtion is built-in string method that checks if all the characters in a string are digits. It returns 'True' if all characters in string are digits(0-9), and 'False' otherwise. 'isdigit()' function does not recognize negative signs or decimal points. Example "-1111" or "11.11" would return 'False' and If the string is empty, isdigit() returns 'False' because there are no characters to look. The isdigit() function only evaluates a given value and does not "accept" or process non-string data types directly. 
.
Return Value

* True: If all characters in the string are digits (0-9).

* False: If the string contains any non-digit characters or is empty.

Limitations

1. Does Not Recognize Fractions or Other Numeric Characters
2. Does Not Handle Negative Numbers or Decimals
3. Does Not Recognize Non-Arabic Digits

Syntax:

string.isdigit()

# .isupper() string method

The python '.isupper()' funtion is a built-in string method that checks whether all the characters in a string are uppercase letters. It returns 'True' if all characers in the sting are uppercase letters (A-Z) and there is at least on characer; otherwise it returns 'False'. If the string is empty, 'isupper()' returns 'False' because there are no characters to look. If the string contains non-alphabetic characters (e.g., digits or punctuation), those are ignored. The isupper() function only evaluates a given string value and do not "accept" or process non-string types directly.

Return Type

* True: If all alphabetic characters in the string are uppercase.
* False: If any alphabetic character is lowercase or if there are no alphabetic characters.

Limitations

1. Non-Alphabetic Characters Are Ignored


Syntax:

string.isupper()

# .islower() string method

The python '.islower()' function is a built-in string method that checks whether all the characters in string are lowercase letters. It returns 'True' if all characters in string are lowercase leters (a-z). otherwise it returns 'False". If the string is  empty, 'islower()' returns 'False' because there are no characters to look. Similar to isupper(), non-alphabetic characters are ignored, and an empty string returns False.The islower() function only evaluates a given string value and do not "accept" or process non-string types directly.

Return Type

* True: If all alphabetic characters in the string are lowercase.
* False: If any alphabetic character is uppercase or if there are no alphabetic characters.

Limitations

1. Non-Alphabetic Characters Are Ignored 

Syntax:

string.islower()

# .upper() string method

The python '.upper()' is  an inbuilt string class method that converts all the lowercase characters in the string into uppercase characters and returns a new string. The Python upper() string method returns a string copy with all the characters changed to uppercase. It does not modify the original string (strings in Python are immutable), but instead returns a new string with all characters in uppercase. The upper() method does not accept any arguments  (it does not accept any parameters). If you try to pass any arguments, it will raise a TypeError.  It only affects lowercase letters. Uppercase letters, numbers, symbols, and whitespace remain unchanged. 

Return Value

* The upper() method returns a new string where all the lowercase letters in the original string are converted to uppercase.
* If the original string contains no lowercase letters, the method returns the original string unchanged.

Limitations

The upper() method does not handle all Unicode characters perfectly, especially in languages with complex case rules. For such cases, you may need to use specialized libraries or functions.

syntax:

string.upper()

# .lower() string method

The python '.lower()' is an in-built string  method used to convert all the characters in a string to lowercase. It is the counterpart of the .upper() method and is commonly used for string manipulation. It does not modify the original string (strings in Python are immutable). Instead, it returns a new string with all characters in lowercase. The method does not take any arguments (it does not accept any parameters). It only affects uppercase letters. Lowercase letters, numbers, symbols, and whitespace remain unchanged.

Return Value

* The .lower() method returns a new string where all the uppercase letters in the original string are converted to lowercase.
* If the original string contains no uppercase letters, the method returns the original string unchanged.

Limitations

1. The .lower() method does not handle all Unicode characters perfectly, especially in languages with complex case rules. For such cases, you may need to use specialized libraries or functions.

syntax:

string.lower()

# .swapcase() string method

The python '.swapcase' is a built-in string method used to  swap the case of all characters in a string. Uppercase letters are converted to lowercase. Lowercase letters are converted to uppercase. Non-alphabetic characters (e.g., numbers, symbols, whitespace) remain unchanged. The .swapcase() method does not accept any arguments. If you try to pass any arguments, it will raise a TypeError. The original string is not modified. Instead, a new string is returned. Characters like numbers, symbols, and whitespace are not affected. The method is locale-aware, meaning it handles special characters and accented letters according to the rules of the current locale.

Return Value

* The method returns a new string where:
  Uppercase letters are converted to lowercase.
  Lowercase letters are converted to uppercase.
  Non-alphabetic characters remain unchanged.

Limitations

1. The method does not affect non-alphabetic characters (e.g., numbers, symbols, whitespace).
2. While .swapcase() handles most Unicode characters, it may not perfectly handle all language-specific case rules.

syntax:

string.swapcase()

# .capitalize() string method

The python '.capitalize' is a built-in string method used to modify the first character of a string uppercase and the rest lowercase. the '.capitalize()' method does not take any arguments. It operates directly on the string it is called on. When using the string we need to remeber that only the first alphabetic character is capitalized; the rest are forced to lowercase. Non-alphabetic characters (like numbers or symbols) at the start of the string remain unchanged. Whitespace at the beginning is preserved. so in general we can use the string '.capitalize()' when formatting user input for consistent capitalization (e.g., names, titles). Standardizing strings where only the first letter should be uppercase.

Return value

* Returns a new string (original string remains unchanged since strings are immutable in Python).
* If the string starts with a non-alphabetic character (e.g., a number or symbol), it remains unchanged, but subsequent letters are lowercased.
* If the string is empty, it returns an empty string ("").

Limitations   

1. Whitespace at the Start Affects Results
2. Does Not Handle Multiple Words Properly

syntax:

string.capitalize()

# .title() string method

The python '.tiltle' is a built-in Python string method that converts the first character of each word in a string to uppercase and makes all other characters in the word lowercase. The original string remains unchanged (strings are immutable in Python). It also capitalizes letters following numbers/symbols. '.tiltle' is mostly used when we want to Simple title formatting where these limitations don't matter, quick formatting of names or simple phrases,it works with user input like any other string method and also when we want consistent capitalization of each word. 

Return value

* First letter of each word is capitalized
* All other letters in each word are lowercase

Limitations

1. Apostrophe Issues
2. Acronym Problems. "NASA and FBI".title()  # Returns "Nasa And Fbi" 

syntax:

string.title()











