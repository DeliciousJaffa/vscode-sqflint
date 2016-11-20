## Version 0.5.6
 * Fixed exec error crashing language server
 * Added global variables to autocompletion
 * Actual variable name is now used for warnings and autocompletion (only lowercase version was used previously)

# Version 0.5.5
 * Fixed autocompletion for BIS functions

# Version 0.5.3

 * **Optimization:** Limited number of sqflint calls when writing code
   * previously, sqflint was called on every change, which caused high CPU usage

# Version 0.5.2

 * Some little optimizations
 * Fixed signature help