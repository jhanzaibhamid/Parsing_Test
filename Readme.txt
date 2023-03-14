the function pars_strr() will take the address of string, parse it, and save data in structure and return error code.

the following work tests the function do
1. if header not match return error
2. if missing data, return error
3. it will check all the data fields and save the relevent values in structure parameters
4. at the end it will check checksum to see whether the data is valid or not
