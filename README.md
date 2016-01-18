#### mnsbtinaction

- chap2
create a folder, run
```
sbt
```
create two files, project/build.properties,
```
sbt.version=0.13.8
```
and build.sbt
```
name:="projectname"
version:="1.0"
```
Three basic commands
```
tasks
settings
inspect <taskname>
```

build a project
```
root
|\
 project/
 - build.properties
 src/
 - main/
   - java/
   - scala/
   - resources/
 - test/
   - java/
   - scala/
   - resources/
```

run the project:

```
compile
run
```
run scala code:
```
console
```
quit console:
```
:q
```



