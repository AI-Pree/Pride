# Pride
Programming Language written for fun and self learning purpose.

# Goals:
- create a compiler that runs on LLVM
- Compiler created using C++
- Reduce the compilation time significantly
- Try to make simple language
- Option to be both interpreted and compiled (for learning purpose)

# Programming Language Design and its Reasoning:
## For operators
- Use ```:=``` for assigning value, coz normally ```=``` would mean equal.

## Design Pattern used:
- follow visitor pattern, for adding operations to a object, in need of adding more functionality afterwards as the scope of language grows bigger. On contrast, adding multiple sub nodes to the object node for the functionaily, would result on creating unmaintainable code. 



# References
### Desgin Pattern
https://en.wikipedia.org/wiki/Visitor_pattern

### Building 
https://llvm.org/docs/tutorial/MyFirstLanguageFrontend/index.html
