# XLS-to-Json-Convertor-
-Made a software which converts the excel file in a required JSON format. 
-Using Html5 FileReader (), I instantiated a FileReader object to read its contents into memory.  
-Simply using FileReader () won’t read the excel file therefore I used XLSX to read the file to Obtain the Current Row as CSV and converting each line to JSON format.  
-Finally I converted JSON into required JSON String using Regx.


# **Working of Software**
-Element.addEventListener(change, function)
-Wherever a file is uploaded a filePicked function is runned .
-In that fuction the content of file was read using the XLSX library
-Each row was obtained as CSV.
-And each row was converted into JSON Format .
-Now to output record , I converted obtained JSON string into JSON object and iterated
through the array of JSON Object and converted obtained data into required format
using Regx.
-Finally the result was displayed .

# **Working**
Just download index3.html file and you are ready to use it !
