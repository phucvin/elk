make test++

make elk

./elk "1+1" -d

time ./elk "let fib = function(n){if(n<2){return n;}else{return fib(n-1)+fib(n-2);}}; fib(30)"