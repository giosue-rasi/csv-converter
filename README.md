# CSV TO CSV CONVERTER - by Giocrom
  version (alpha) 2.6


## WHAT IT DOES
The CSV TO CSV CONVERTER will change the current separator of your .csv files to
any other character you desire, without corrupting data, and with only one
simple terminal command!


## HOW TO USE IT
Once installed, put the file you want to convert inside of the "Input" folder
and then start the conversion with your terminal like this:
`./csvconverter input_file.csv output_file_name current_separator new_separator`

You'll find the converted file in the "Output" folder!


## PARAMETERS
The Csv Converter takes a minimum of three and a maximum of 4 parameters

- The first one is the file you want to convert, complete of the .csv extension
  `e.g. input_file.csv`
  It can't be omitted, obviously.

- The second one is the name of the output file, which doesn't have to be
  complete of the .csv extension
  `e.g. output_file_name OR output_file_name.csv`
  This parameter is optional, if you don't specify an output the program will
  save the conversion in a file called "converted.csv"

- The third one is the separator your .csv file is currently using

- The forth one is the separator you'd like to convert to


## SOURCES
Csv Documentation - https://datatracker.ietf.org/doc/html/rfc4180


## THINGS TO CONSIDER
- Fields containing line breaks (CRLF), double quotes, spaces, and commas
  should be enclosed in double-quotes.

- If fields are not enclosed with double quotes, then double quotes may not
  appear inside the fields.

- If double-quotes are used to enclose fields, then a double-quote
  appearing inside a field must be escaped by preceding it with
  another double quote.

- The last field in the record must not be followed by a comma.


## FORMAT EXAMPLE:
    [field_name,field_name,field_name CRLF]
    "a""a""a","bb CRLF
    b","ccc" CRLF
    zzz,yyy,xxx [CRLF]
