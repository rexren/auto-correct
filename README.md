# auto-correct
JAVA 拼写检查平台

无意中翻到大神 Peter Norvig 写的一篇 [How to Write a Spelling Corrector](http://norvig.com/spell-correct.html)，非常感兴趣。
计划用java重写，同时做成一个可配置的平台，并提供REST API用于查询。

##设计
平台分为两个部分，autocfun-lib和autocfun-site，lib用于提供一个通用的校验库，site是一个简单的验证web系统，可以用于检查库并提供简单的Restful API
