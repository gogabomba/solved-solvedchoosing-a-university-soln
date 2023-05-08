Download Link: https://assignmentchef.com/product/solved-solvedchoosing-a-university-soln
<br>
(Absolutely no two-dimensional arrays may be used)

Purpose:Analyze and summarize the data collected on United States universities.

In this program you will write a C++ program to analyze a small subset of the data that has been collected. See file universities.txt .

Use precisely seven parallel arrays: one for name of university, one for state, one for city, one for yearly tuition, one for enrollment,one for average freshman retention, and one for the percent of students who graduate within six years. Note that the percentage ofstudent accepted is not stored. An output file is opened in main() and remains open until the end of the execution.

Input:

Write a function to input the name of each university, the two-letter abbreviation for the state, the city, tuition, enrollment, averagefreshman retention rate, percent that graduate within six years.

Repeat until end of file. Assume a maximum of 1000 universities. Use getline(file, string name) to input text with spaces. You willfind a very mischievous ‘
’ character to deal with both after the name of the university and at the end of the five numerical values.You will enjoy knowing about file.ignore().

Output: Write a separate function to output to the file all universities with name of university, state, tuition, enrollment, percentageretention for freshman, and percentage that have graduated after six years for each. NOTE THAT THE CITY IS NOT OUTPUT.

Processing:Call the output function to output to a file all data in the original order.

Write a separate function to compute and return the average tuition for all universities. Do not output from this function but returnthe value and print it out to the screen from main().

Write a function to ask the user for maximum he/she can pay for tuition. List to the screen the name only of all schools with thatamount or less for tuition. Output is from within the function.

Write a function to prompt the user for a two-letter abbreviation for a state. Output to the file from this function all information forcolleges within that state or output message “No colleges in XX state in the list”.

Write one and only one function to return the subscript of the university with the lowest tuition. There is no output in thisfunction. Do not assume a sorted array. In main(), the name(s) of the university or universities with this low tuition and the amountof the tuition are output to the screen.

Use a selection sort to sort universities by enrollment in ascending order. This is written as a separate function with no output.

Write the sorted array to the file.

THEME ISSUES: one-dimensional arrays, if statements, file input, file output, searching, sorting

Absolutely no two-dimensional arrays, no structures and no menu function.

Sample of the output before sorting (this is what display after the output function is called) :

UniversityState Tuition Enrollment%Fresh%Graduate

Succeedin six yearsPrinceton UniversityNJ 41820.00801498.00%97.00%Harvard UniversityMA 43938.00

1988297.00%97.00%Yale UniversityCT 45800.001210999.00%98.00%Columbia UniversityNY 51008.002360699.00%96.00%Stanford UniversityCA 44757.001813698.00%96.00%University of ChicagoIL 48253.001253999.00%93.00%Massachusetts Institute of TechnologyMA 45016.0011301

98.00%93.00%. . .

How should you do this? Follow these steps carefully!!!!!!!STEP 1Write main() and call getData() function which only opens file. Debug.STEP 2Complete getdata(). Debug.STEP 3Write output function. Output is directed to the output file and NOT the screen. Debug.STEP 4Write the function to compute the average of tuition at all schools. Output this value to the screenfrom main(). Debug.STEP 5Write a function that will output the name only of each university where the tuition is less than or equalto the given amount. Output to the screen.STEP 6Write a function to prompt the user for a two-letter abbreviation for a state. Output to the file from thisfunction all information for colleges within that state or output message “No colleges in XX state in thelist”. Debug.STEP 7Write one and only one function to return the subscript of the university with the lowest tuition. Thereis no output in this function. Do not assume a sorted array. In main(), the name(s) of the university oruniversities with this low tuition and the amount of the tuition are output to the screen.STEP 8

Write a separate function using the selection sort to sort universities by enrollment in ascending order.Debug

CheckpointsPossibleDocumentation throughout to explain general outline of program.5Minimum of three (3) comments in each function(Purpose: Pre: Post:)Include name, e-mail, and lab# as comment and printed to outputFunction main() which implements each step outlined in the processing section of the lab write-up.5Input function fills array for names plus four numerical arrays. It should return the number of5universities.Output function5Function to compute the average of tuition at all schools4Function to output to screen universities where tuition is less than or equal to given amount.4Function to prompt the user for a two-letter abbreviation for a state. Output to the file from this function4all information for colleges within that state or output message “No colleges in XX state in the list”.Write one and only one function to return the subscript of the university with the lowest tuition. There is

4no output in this function. Do not assume a sorted array. In main() the name(s) of the university oruniversities with this low tuition and the amount of the tuition are output to the screen.Function using the selection sort to sort universities by enrollment in ascending order.4Totals40