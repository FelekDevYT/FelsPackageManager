# FelsPackageManager

This is package manager for [Fels programming language](https://github.com/FelekDevYT/Fels-programming-language)

## How you can use this package manager

To use package manager working only for FELS PROGRAMMING LANGUAGE!!!

To use PM you should write to run file:
```
#linklude "Buffer.fels"
```

The #linklude directive load from PM file with name in ``""``

And import you file for you can use it!

[Full guide](https://github.com/FelekDevYT/Fels-programming-language)

## List of libraries(About Dependencies)

| Name          | Dependencies | about                | lib class funcs                                                                                                                                               |   |   |   |   |   |   |
|---------------|--------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|---|---|---|---|---|---|
| Steck         | no           | Steck class          | push(text),peek(),pop(),empty()                                                                                                                               |
| StringBuilder | no           | apply strings        | append(text),set(text),get()                                                                                                                                  |
| Map           | no           | Map type lib         | set(name,value),get(name),size(),isEmpty()                                                                                                                    |
| List          | no           | List type            | size(),set(pos,str),get(pos),isPosEmpty(),add(str)                                                                                                            |
| Info          | no           | get info about PC    | getOSName(),getOSVersion(),getUserHome(),getJavaHome(),getJavaVersion(),getOSArch(),getPathSeparator(),getUserDir(),getUserName()                             |
| Funit         | Exceptions   | unit testing         | assertEquals(v1,v2),assertNotEquals(v1,v2),assertSameType(v1,v2),assertTrue(v1),assertFlase(v2)                                                               |
| Exceptions    | no           | Add typed exceptions | ArgumentsMissmatchException(text),OperationIsNotSupportedException(text),PanicException(text),TypeException(text),felsAPIException(text),FunitException(text) |
| Converter     | Exceptions   | Converting           | toNumber(v1),toBoolean(v1),getTypeOf(v1)                                                                                                                      |
| Colors        | no           | Coloring             | reset(v),red(v),green(v),blue(v),<br>white(v),black(v),purple(v),yellow(v),cyan(v)                                                                            |
| Buffer        | no           | Buffer of word       | set(text),get(),append(text)                                                                                                                                  |
| ArrayDeque    | no           | ArrayDeque type      | add(text),addLast(text),push(text),size(),clear(),getFirst(),getLast()                                                                                        |

