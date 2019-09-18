# Answers Summary

## Question Format
Please answer the following 4 questions for each unit test:
1. What is the knowledge point of the test? Where is the official document to the knowledge point?
2. Why the test failed at first?
3. Why you corrected the test that way?
4. Do you have further questions on this knowledge point?

## StringTest
#### should_be_immutable
1. This is for me to learn the different optional functions and replace method in Java.
https://www.baeldung.com/java-optional
https://www.javatpoint.com/java-string-replace
2. Because the expected result is empty.
3. Corrected the test by modifying aresame to show optional value of false.
4. None.

#### all_modification_method_will_create_new_string
1. This is for me to learn the different optional functions, trim method in Java.
https://www.baeldung.com/java-optional
https://www.javatpoint.com/java-string-trim
2. Because the expected result is empty.
3. Corrected the test by modifying aresame to show optional value of false.
4. None.

#### will_create_new_string_when_concat
1. This is for me to learn the different optional functions, concatenating in Java.
https://www.baeldung.com/java-optional
2. Because the expected result is false.
3. Corrected the test by modifying aresame to show optional value of false.
4. None.

## Question Format on Take String Apart
1. What if the input arguments is out of range of the string?
2. What will happen if the the starting index is greater than the ending index?
3. What will happen if the input string is of null reference?


#### should_taken_string_apart
1. This is for me to learn manipulating the given string inputs in Java.
https://beginnersbook.com/2013/12/java-string-substring-method-example/
2. Test failed first because the part of the string is null
3. Corrected the test by modifying partOfString variable to get particular part of the string in original string variable.
4. None.

1.
2. It will result to Index Out of Bound Exception
3. It will result to Null Pointer exception



#### should_taken_string_apart_continued
1. This is for me to learn manipulating the given string inputs in Java.
https://beginnersbook.com/2013/12/java-string-substring-method-example/
2. Test failed first because the part of the string is null
3. Corrected the test by modifying partOfString variable to get particular part of the string in original string variable.
4. None.

1.
2. It will result to Index Out of Bound Exception
3. It will result to Null Pointer exception

#### should_break_string_into_words
1. This is for me to incorporate string manipulation in other data types such as array.
https://beginnersbook.com/2013/12/java-string-substring-method-example/
2. Test failed first because array word is null and it will not be equal to the given string array in assert.
3. Corrected the test by getting the substring required and put it in the array.
4. None.

#### should_break_string_into_words_customized
1. This is for me to incorporate string manipulation in other data types such as array.
https://beginnersbook.com/2013/12/java-string-substring-method-example/
2. Test failed first because array word is null and it will not be equal to the given string array in assert.
3. Corrected the test by getting the substring required and put it in the array.
4. None.

#### should_create_ascii_art
1. This is for me to incorporate and learn more on using loops, escaped characters (line feed) and String builder.
http://www.corejavaguru.com/java/strings/stringbuilder
2. Test failed first because the string builder object is only created and no actually input values at all.
3. Corrected the test by appending necessary characters in the requirement and used loops and escaped character to create the output.
4. None.

#### should_calculate_checksum_of_a_string
1. I learned about Ascii value equivalent of the letters, as well as converting letter to ascii value in code.
https://www.codevscolor.com/java-program-find-ascii-character/
2. Test failed first because it does not have the logic that will get the asscii values.
3. Corrected the test by getting the characters in the string then getting the values by typecasting the character to int then add it to the sum.
4. None.

#### should_convert_unicode_escape
1. I learned about outputting a Unicode by using invoking \u for system to know that input is in unicode
http://hints.macworld.com/article.php?story=20050208053951714
2. Test failed first because the input is initially in null.
3. Corrected the test by using \u then follow the assigned code for each character.
4. None.


#### should_reverse_a_string
1. I learned about using String builder in order to manipulate a string without using loops
https://moometric.com/development/java/reverse-a-string-in-java/
2. Test failed first because the input is initially in null.
3. Corrected the test by using String builder then reverse the original string then convert to string.
4. None.

#### should_compare_string_with_different_cases
1. This is for me to utilize optional functions in Java.
https://www.baeldung.com/java-optional
2. Because the expected result is empty.
3. Corrected the test by modifying actualResultOfEqual and actualResultOfEqualIgnoreCase to false and true respectively.
4. None.

#### should_format_string
1. This is for me to learn to use string format.
https://dzone.com/articles/java-string-format-examples
2. Because the initial expected text is null.
3. Corrected the test by modifying expectedText based on given input and on the String format.
4. None.