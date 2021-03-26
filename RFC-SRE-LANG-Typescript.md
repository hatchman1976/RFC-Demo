# RFC XXXX - TypeScript Language for SRE

To continually improve LI's SRE code base we need to adopt more modern conding langauges to support containerised workloads and cloud-native applications.


## Why should we adopt TypeScript

Typescript is a modern type-safe langauge that transpiles to JavaScript but provides type-safety ensuring that the chance of bugs and run-time errors are reduced than when using JavaScript. It is highly performant and supports parallel programming through the use of async/await functions and other modern JavaScript frameworks.

TypeeScript also has support for Generics, Classes but does enforce manadatory OOP programming. This means that creating hierarchy class object structures can be used when required

Typescript also supports anonymous and asynchronous functions making it similar to functional programming languages and thus more efficient for processing large loads of data.

TypeScript can run as a front-end web language as popular JavaScript frameworks like React and Vue integrate well with TypeScript. It is also compatible with Node.js, which can be used to achieve server-side functionality therefor enabling us to adopt a language that can consolidate both front and backend work.

## What languages does this deprecate

The main scripting language used by SRE's is Python. While effective, Python is not as performant as TypeScript as it is not asynchronous at it's core. and therefore can become unreliable when needing to perform large and complex data processing tasks at the same time, across multiple machines.

Python suffers from version compatibility, most notable the 2.7 to 3.0 upgrade which changed significant features of the langauge and broke a lot of exsiting scripts. As TypeScript transpiles to JavaScript it does not suffer the same drawbacks making it more portable across different JavaScript engines

## What happens if we do not adopt TypeScript

SRE's will become more insular and upset!
