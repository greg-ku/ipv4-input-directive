# IPv4 Input Directive

An angular directive module that provides Windows-style IP input.

## Installation

```
npm install --save ipv4-input-directive
```

or

```
bower install --save ipv4-input-directive
```

## Usage

### import module

```
var app = angular.module('demoApp', ['ipv4-input-directive']);
```

### input directive

```
<gk-ipv4-input></gk-ipv4-input>
```

### attributes

- value

mapping the ip address string to variable

```
<gk-ipv4-input value='addr'></gk-ipv4-input>
```

- valid

mapping the valid bool to variable

```
<gk-ipv4-input valid='isValid'></gk-ipv4-input>
```

- rwd

styling the input to responsive

```
<gk-ipv4-input rwd></gk-ipv4-input>
```

## Demo
[Try it](https://rawgit.com/greg-ku/ipv4-input-directive/master/demo.html)

## Change log

### 1.0.1

- refine responsive css
