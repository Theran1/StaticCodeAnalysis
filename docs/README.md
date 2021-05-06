
## Introduction

Static Code Analysis (also known as Source Code Analysis) is usually performed as part of a Code Review (also known as white-box testing) and is carried out at the Implementation phase of a Security Development Lifecycle (SDL). Static Code Analysis commonly refers to the running of Static Code Analysis tools that attempt to highlight possible vulnerabilities within ‘static’ (non-running) source code by using techniques such as Taint Analysis and Data Flow Analysis.

Ideally, such tools would automatically find security flaws with a high degree of confidence that what is found is indeed a flaw. However, this is beyond the state of the art for many types of application security flaws. Thus, such tools frequently serve as aids for an analyst to help them zero in on security relevant portions of code so they can find flaws more efficiently, rather than a tool that simply finds flaws automatically.

### What About SCA Brother? Dynamic Code Analysis? Whats the difference?

//Imagen

When performing comprehensive source code reviews, both static and dynamic testing should be performed. Static analysis source code testing is adequate for understanding security issues within program code and can usually pick up about 85% of the flaws in the code.

Dynamic code review has the additional ability to find security issues caused by the code's interaction with other system components like SQL databases, application servers or Web services. (Parameters are sent to back-end servers for processing, which could be modified before returning.) Dynamic code reviews, presented with a wide range of inputs and security tests, will generally pick up about 85% of the flaws present in the code.


### Developing on the concept of Static Code Analysis:

SCA helps development teams that are under pressure. Quality releases needed to be delivered on time. Coding and compliance standards need to be met. And mistakes are not an option and that’s why development teams are using static analysis tools.

This type of analysis addresses weaknesses in source code that might lead to vulnerabilities. Of course, this may also be achieved through manual code reviews. But using automated tools is much more effective.

SCA is commonly used to comply with coding guidelines — such as MISRA. And it’s often used for complying with industry standards — such as ISO 26262.

//Imagen
//Imagen

### Benefit

There are several benefits of static code analysis tools — especially if you need to comply with an industry standard.

The best static code analysis tools offer speed, depth, and accuracy. 

*Speed* 

It takes time for developers to do manual code reviews. Automated tools are much faster.

Static code checking addresses problems early on. And it pinpoints exactly where the error is in the code. So, you’ll be able to fix those errors faster. Plus, coding errors found earlier are less costly to fix.

*Depth* 

Testing can’t cover every possible code execution path. But a static code analyzer can.

It checks the code as you work on your build. You’ll get an in-depth analysis of where there might be potential problems in your code, based on the rules you’ve applied.

Here's an example of in-depth code analysis in Helix QAC, another tool for SCA, this one specifically for C/C++.

//Imagen

*Accuracy* 

Manual code reviews are prone to human error. Automated tools are not.

They scan every line of code to identify potential problems. This helps you ensure the highest-quality code is in place — before testing begins. After all, when you’re complying with a coding standard, quality is critical.  



Here are a few things to consider when deciding which tool is right for you.

Programming Language
Analyzers are designed for many different programming languages. So, it’s important to choose a tool that supports your language.

Standards
One the primary uses of static analyzers is to comply with standards. So, if you’re in a regulated industry that requires a coding standard, you’ll want to make sure your tool supports that standard.

