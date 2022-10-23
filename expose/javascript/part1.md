1. values added: 20
2. final result: 20
3. values added: 20
4. The code returns an error because result is defined using let, which has block scope, and line 13 lies outside of the if/else block the variable exiosts inside of. 
5. The code never makes it to line 9 because at line 7 it tries to assign a value to the result variable which is of the const type, meaning javascript throws an error when someone tries to assign something to it
6. Again, the code never makes it this far because it errors out at line 7. If it were to make it this far, it would fail again because the const keyword has block scope line the let keyword, and line 12 is out of the block it was declared in.