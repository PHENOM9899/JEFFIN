/*
declare 
a number;
b number;
c number;
begin
a := 10;
b := 5;
c := a + b;
dbms_output.put_line('sum of a and b is '||c);
end;
*/

declare
a number;
b number;
c number;
begin
a:=:a;
b:=:b;
c:=a+b;
dbms_output.put_line('Sum of a and b is '||c);
end;

declare
a number;
b number;
c number;
begin
a:=:a;
b:=:b;
c:=a*b; Multiply
dbms_output.put_line('Sum of a and b is '||c);
end;

declare
a number;
b number;
c number;
begin
a:=:a;
b:=:b;
c:=a/b; divide
dbms_output.put_line('Sum of a and b is '||c);
end;

declare
a number;
b number;
c number;
begin
a:=:a;
b:=:b;
c:=a**b; power 
dbms_output.put_line('Sum of a and b is '||c);
end;

declare 
msg varchar2(20);
begin
msg:='hello world';
dbms_output.put_line(msg);
end;
