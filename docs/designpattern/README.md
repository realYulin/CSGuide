# 设计模式

这里会讲解常见的一些设计模式，在讲具体的设计模式之前，先看一下设计模式的六大原则。

这六大原则是面向对象设计和编程的基本原则，核心目的就是编写可维护、可扩展、可复用的代码。

包括：

* 单一职责原则（Single Responsibility Principle, SRP）

一个类应该仅有一个引起它变化的原因，简单说，就是每个类应该负责一项功能，避免过于复杂的职责分配，功能太复杂的类往往不利于维护。

* 开放开闭原则（Open/Closed Principle, OCP）

软件实体（类、模块、函数等）应该对扩展开放，对修改关闭，意思是在不修改已有代码的情况下，可以通过扩展实现新功能。

* 里氏替换原则（Liskov Substitution Principle, LSP）

子类应该能够替换其父类，并且在使用子类替换父类后，程序的功能不受影响。这意味着子类应遵循父类的行为约定，不要违反父类的规定。


* 接口隔离原则（Interface Segregation Principle, ISP）

客户端不应该被迫依赖于它不使用的接口。应该将复杂的接口拆分为多个独立的接口，以便客户端只需了解与其相关的最小接口集合。

* 依赖倒置原则（Dependency Inversion Principle, DIP）

高层模块不应该依赖低层模块，二者都应该依赖于抽象。抽象不应该依赖于细节，细节应该依赖于抽象。这意味着要依赖于接口或抽象类，而不是具体实现。

* 迪米特法则（Law of Demeter, LoD）

一个对象应该尽量少地与其他对象直接交互。也称为“最少知道原则”，意味着每个对象应尽量降低对其他对象的依赖，减少耦合。
