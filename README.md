Download Link: https://assignmentchef.com/product/solved-class-named-cryptgram-java
<br>
Design a class Named CryptGram.java with the following requirements:  Data Members: a Letter(it is provided) array named orderedFrequency to store frequency of the 26 alphabetic letters.

Methods:

createLetterFrequencyFromFile(File file)       getFrequencyByChar(char letter)

encode(String textToBeEncoded)

decode(String textToBeDecoded)




The method: createLetterFrequencyFromFile, reads a file and creates the letter frequency, the letter frequency array MUST by sorted by frequency, for example, the first three Letter elements in the array may look like: d[2], r[5], a[6], which means d appears in the file twice, r five time, and a six times. If the frequencies are ties, then being ordered by alphabetic order. For instance, e[9]  and c[9], c[9] should be placed before e[9].

The method: getFrequencyByChar, returns the number of times the char passed as argument appears in the file

The method: encode, encodes the String and returns encoded String. The text to be encoded is encrypted as follows: each character in the text will be encrypted to the character in the letter frequency array: orderedFrequency. For example, letter a or A will be encrypted to the letter of the first element in the orderedFrequency array. The letter z or Z will be encrypted to the letter of the last element in the orderedFrequency array.

The method: decode, reverse the encode process and decrypt the text (ignore cases)




A demo program is provided for testing. To run the demo, click on the FrequencyEncryptDriver.class, provide file name and text to be encrypted in the argument list. For example *cryptgram.txt java Note: class name, variable name, and method names MUST be the same as specified.


