**This is some useful code:**

**1. Debugging in Python**

   From the Command Line: It is the easiest way of using a debugger. You just have to run the following command in terminal.

   This statement loads your source code and stops execution on the first line of code.

       python -m pdb (add your filepath and file name here)

   Can also use the built-in _Breakpoint()_ function within code, invokes debugger from pdb module automatically at whatever point you call the function, better for stepping through / debugging specific sections of code, rather than whole program.

   * c: continue execution.
   * q: quit the debugger/execution.
   * n: step to next line within the same function.
   * s: step to next line in this function or a called function.


**2. Spreadsheets**

   This is the syntax for VLOOKUP.

         =VLOOKUP(lookup_value, table_array, col_index_number,[range_lookup])

   * lookup_value: This specifies the value that you want to look up in our data.
   * table_array: This is the location where the values are present in excel.
   * col_index_number: This specifies the column number from where we need to return the value.
   * range_lookup: This has two options;
      * if the value is set to FALSE, that means we are looking for an exact match.
      * If the value is TRUE, then we are looking for an approximate match.
    

   Use =XLOOKUP for cross-referencing to different tab.

   Use $ infront of each cell reference element to maintain absolute referencing when copying formula down column of cells.<br>
      * _e.g. =XLOOKUP(A12,Data!$A$2:$A$6,Data!$B$2:$C$6,)_


**3. Linear Search**

   def linearSearch(arr, x):<br>
      for i in range(len(arr)):<br>
         if arr[i] == x:<br>
            return i<br>
      return -1<br>
