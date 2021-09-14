let fun fib(n)=
let val c=0 in 
let val a=0 in 
let val b=1 in
let val x=n in
{
while 0<x do
{
c:=a+b;
a:=b;
b:=c;
x:=x-1
};
c
}
end
end
end
end 
in fib(8) 
end;

