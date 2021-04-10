

# Credit Score Lookup Example
> This example demonstrates a privacy preserving search against an encrypted 
database and it is implemented using the [Brakerski-Gentry-Vaikuntanathan](http://eprint.iacr.org/2011/277) 
(BGV) scheme. The database is a key-value store pre-populated with the 
English names of countries and their capital cities from the continent of 
Europe. Selecting the country will use HElib to perform a search of the 
matching capital.


# Depedencies
[C++14](https://gcc.gnu.org/projects/cxx-status.html)  
[Helib](https://homenc.github.io/HElib/)  

# To Compile
Specify Helib directory path in the following command
```
cmake -Dhelib_DIR=/home/default/helib_install/helib_pack/share/cmake/helib /BGV_ssn_db_lookup ..
make -j16
```
