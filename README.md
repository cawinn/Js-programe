# Js-programe
var city = "Salem";
console.log("name of the city="+city);

function mycity()
{
    console.log("name of the city="+city);
}
function  modifiedmycity()
{
    console.log("name of the city="+city);
}
mycity();
modifiedmycity();



//multiple variable in single statement//

var a=10,b=20,c=50;
function add()
{
    console.log("a+b+c");
}
add();

//o/p--->undefined//hoisting
console.log(data);
var data=50;

//o/p---->50//
var data=50;
console.log(data);

//when value is changed for a desired keyword the old value is removed//
let wish;
wish = "welcome"
wish = "hello"
console.log(wish);

let greet = wish;
console.log(wish);
console.log(greet);

//qualification cannot be access before the initialization//
qualification = "BE";
console.log(qualification);

let name_student = "Shiva";//global scoped variable//
function getstudentname()
{
    console.log(name_student);
}
function gettrainername()
{
    console.log(name_student);
}
getstudentname();
gettrainername();

function gettrainername()
{
    let company = "TCS";
    console.log(name_student);
    console.log(company)
}

gettrainername();

//js variable declaration using let keyword//
function iterateme()
{
    let i = 4;//let keyword boundary with in the loop//
    for (let i=0;i<6;i++)
    {
        console.log("loop"+i)
    }
    console.log("final value of i outside the loop:"+i);
}
iterateme();

//js variable declaration using var keyword//var  keyword will work inside and outside the loop//
function iterateme()
{
    var i = 4;
    for (var i=0;i<=6;i++)
    {
        console.log("loop"+i)
    }
    console.log("final value of i outside the loop:"+i);
}
iterateme();

let $=10;
let _=20;
let sum=$+_;
console.log(sum);
//camelcase ----> myData
