# IPv4 Input Directive

An angular directive module that provides Windows-style IP input.

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
https://rawgit.com/greg-ku/ipv4-input-directive/master/demo.html
