
## Introduction

Static program analysis is the analysis of computer software that is performed without actually executing programs, in contrast with dynamic analysis, which is analysis performed on programs while they are executing. In most cases the analysis is performed on some version of the source code, and in the other cases, some form of the object code.

The term is usually applied to the analysis performed by an automated tool, with human analysis being called program understanding, program comprehension, or code review. Software inspections and software walkthroughs are also used in the latter case.

### What About SCA Brother? Dynamic Code Analysis? Whats the difference?

//Imagen

When performing comprehensive source code reviews, both static and dynamic testing should be performed. Static analysis source code testing is adequate for understanding security issues within program code and can usually pick up about 85% of the flaws in the code.

Dynamic code review has the additional ability to find security issues caused by the code's interaction with other system components like SQL databases, application servers or Web services. (Parameters are sent to back-end servers for processing, which could be modified before returning.) Dynamic code reviews, presented with a wide range of inputs and security tests, will generally pick up about 85% of the flaws present in the code.
