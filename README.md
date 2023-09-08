# JNA-GO-JAVA

Taken from here: https://medium.com/learning-the-go-programming-language/calling-go-functions-from-other-languages-4c7d8bcc69bf

```
# build go code for java consumption
go build -o awesome.so -buildmode=c-shared awesome.go

# compile java Client code
javac -cp jna.jar Client.java

# run java Client code
java -cp .:jna.jar Client
```

