## JDK Distributions

Oracle JDK
- Closed Source(Oracle)
- paid license

Open JDK
- Open Source(Oracle, Redhat, Microsoft, Community..)
- GPL2 License
- Be required TCK(OpenJDK Community TCK License Agreement)

[Open JDK Distributions(21버전 이후 TCK 획득)](https://openjdk.org/groups/conformance/JckAccess/jck-access.html)
- Amazon Corretto
- Azul Zulu Community
- Bellsoft Liberica JDK
- Eclipse Temurin(AdoptOpenJDK HotSpot)
- GraalVM Community Edition
- Oracle GraalVM
- Oracle OpenJDK
- SAP SapMachine

## Release cycle

**Oracle JDK, Open JDK Release cycle**
- 6개월마다 Major 버전 업데이트(Java 10 이후)
- 2년마다 LTS 버전 업데이트(Java 17 이후부터, 이전엔 3년마다 업데이트)

**LTS**
- 8 (2014~2030)
- 11 (2018~2032)
- 17 (2021~2029)
- 21 (2023~2031)
- 25 (2025~2033)

## Features By Version

**[1.8](_1.8)** ~2030  
Lambda expressions
Method references
Functional interfaces  
Stream API
Optional Class  
Interface Static, Default method  
Base64 Encode, Decode  
Collcetors Class  
forEach()  
Date/Time API  
StringJoiner final Class (java.util)

**[11](_11)** ~2026   
(Java 9)  
Java Platform Module System  
Interface Private Method  
HTTP 2 Client  
JShell

(Java 10)  
Local Variable Type Inference (var keyword)  
Garbage Collector Interface

(Java 11)
Http Client API  
Launch Single-File Programs without compilation  
Files.readString(), Files.writeString()  
Optional.isEmpty()  
String New method(isBlank, lines, strip)

**[17](_17)** ~2029  
(Java 12)  
Compact Number Formatting  
Collectors.teeing (Stream API)  
Files.mismatch(path, path)

(Java 14)  
Helpful NullpointerExceptions  
Switch Expressions

(Java 15)  
Text Blocks(Multiline strings)

(Java 16)  
Record Class  
Pattern Matching for instanceof  
Packaging Tool  
PermGem -> Meta Space

(Java 17)  
spring6, springboot3  
Sealed Classes  
Pseudo random number API

**[21](_21)** ~2031  
(Java 18)  
UTF-8 by default  
Simple Web Server  
Internet-Address Resolution SPI  
JAVA API Documentation - @Snippet  
Deprecate try-catch-finally

(Java 21)  
Sequence Collections  
Record Pattern  
Pattern Matching for Switch  
Virtual Threads  
Key Encapsulation Mechanism API  
String Templates(Preview)  
Unamed Classes and Instance Main Methods(Preview)  
Structured Concurrency(Preview)  
