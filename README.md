# Simple Web App

This app runs a web server that performs simple calculations and writes the results to a local file.

To build:

```
go build .
```

To run:

```
./simplewebapp
```
The input is:

ID
OP
VAL1
VAL2

ID is any string
OP is `+`, `-`, `*`, or `/`
VAL1 and VAL2 are integers

Sample input:

```
CALC_1
+
3
2
```

Sample call to endpoint:

```
curl -X POST localhost:8080 --data 'CALC_2                                    
*
100
3000'
```

