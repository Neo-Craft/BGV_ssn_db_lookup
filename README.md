

# Credit Score Lookup Example
> This example demonstrates a privacy preserving search against an encrypted 
database and it is implemented using the [Brakerski-Gentry-Vaikuntanathan](http://eprint.iacr.org/2011/277) 
(BGV) scheme. The database is a structured data populated with Social Security
numbers, and their associated name, sex, address, age and credit score. 
Selecting the SSN will use HElib to perform a search of its matching 
credit report.


# Depedencies
[C++14](https://gcc.gnu.org/projects/cxx-status.html)  
[Helib](https://homenc.github.io/HElib/)  

# To Compile
Specify Helib directory path in the following command
```
cmake -Dhelib_DIR=/home/default/helib_install/helib_pack/share/cmake/helib /BGV_ssn_db_lookup ..
make -j16
```
