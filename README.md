# Reverse-the-number
// Reverse 108
// Way 1
var num=108;
var output = 0;
var rem;
while(num>0)
{
    rem = num%10;
    output = output*10 + rem;
    num = Math.floor(num/10);
}
console.log(output);

