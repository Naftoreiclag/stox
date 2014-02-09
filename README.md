stox
====
Licensed into [Public Domain](http://unlicense.org/)

Convert std::string into a bunch of different arithmetic types. (e.g. int, long, short...)

    #include <string>
    #include "stox.hpp"
    
    std::string str;
  
    stox::stos(str); // converts to short
    stox::stous(str); // converts to unsigned short
    stox::stoi(str); // converts to int
    stox::stoui(str); // converts to unsigned int
    stox::stol(str); // converts to long
    stox::stoul(str); // converts to unsigned long
    stox::stoll(str); // converts to long long
    stox::stoull(str); // converts to unsigned long long

Each function has the prefix *sto* which stands for **S**tring **To**.
The suffix is composed of the initials of the type being converted to.

Examples:
* *stoi* = **S**tring **To** **I**nteger
* *stoui* = **S**tring **To** **U**nsigned **I**nteger
* *stoull* = **S**tring **To** **U**nsigned **L**ong **L**ong
