var d = prompt("Ismingiz");

console.log(d.length);
console.log(d.slice(0, 100))
console.log(d.charCodeAt(0));
console.log(d.charCodeAt(1));
console.log(d.charCodeAt(2));
console.log(d.charCodeAt(3));
console.log(d.charCodeAt(4));
console.log(d.charCodeAt(5));
console.log(d.charCodeAt(6));
console.log(d.charCodeAt(7));
console.log(d.charCodeAt(8));
console.log(d.charCodeAt(9));
console.log(d.charCodeAt(10));
console.log(d.charCodeAt(11));





var d =prompt("Ism");
var res1 = d.slice(0, 1).toUpperCase();
var res2 = d.slice(0, 1).toLocaleLowerCase();
var res3 = d.slice(1)
if (d.slice(0, 1) == res1) {
    console.log(res2.concat(res3));
}
else {
    console.log(res1.concat(res3));
}

