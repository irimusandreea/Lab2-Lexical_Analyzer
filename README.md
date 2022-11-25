#Lexical Analyzer

 Statement:
 
  The scanner's input will be a text file containing the source program, and will produce as output the following:

    PIF - Program Internal Form

    ST - Symbol Table

 In addition, the program should be able to determine the lexical errors, specifying the location, and, if possible, the type of the error.
 
 The following commands were used:

    lex lex-analizer.l
    gcc lex.yy.c
    ./a.out sum.txt

 The first command generates the lex.yy.c file, while the second one generates the executable a.out.

![image](https://user-images.githubusercontent.com/102168199/203989789-396f2352-f15f-4351-8fc3-7f7d0da45cc6.png)

![image](https://user-images.githubusercontent.com/102168199/203990237-c96704ea-50f7-44f1-b432-96232ddeada9.png)
