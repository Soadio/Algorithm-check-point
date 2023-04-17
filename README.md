# Algorithm-check-point
Sentence Counter


sentence : STRING
vowels: CHAR[]
sentence := input("Enter a sentence")

vowels := "a,e,i,o,u"
vowel_count := 0

FOR i from 1 TO LEN(sentence)
DO if sentence [i] in vowels
 vowels_count += 1
 
 
WRITE (vowels_count)
