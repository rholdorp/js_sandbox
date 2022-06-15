- uses plugin: live server: open html on local host
- uses plugin: bracket pair colorize
- uses plugin: javascript es6 snipplets

- key for emet in html files by default is <tab> e.g. <h1+<tab> shortcut for

# Section 2:

## section 2.5:

- In Index.html
  vscode uses emet by default: type ! tab to get basic html layout

## section 2.6:

- console: can execute javascript, query dom, etc

console.log
.error
.table
.clear
.warn
.time and .timeEnd

## sections 2.7:

var, let, const
modern only uses let and const
typical camelCase

let and var simular, except for block

const is defined fixed value. Can change/mutate but not re-assign

e.g.
const person = {
name: 'John',
age: '42'
}

person.name = 'Sara';

## section 2.8 (datatypes)

primitive data types = directly in the variable (on stack)
reference data types = accessed via reference (on heap)

primitive datatypes:
sting, numbers, booleans, null, undefined, symbols(es6)

reference types: arrays, objects, functions, dates

dynamically typed ... e.g. can change from string to number

## section 2.9 (type conversion)

- number to sting:
  Sting(number);

- string to number:
  Number(string);

## section 2.10 (math):

val = Math.PI;
.E;
.round();
.abs();
.random()

## section 2.11 (strings)

string.lenght;
.toUppercase();
.substring(); // filter part out
.slide(); // slide sting in 2
.split(" "); //split on space
.include("n"); //bool if includes
