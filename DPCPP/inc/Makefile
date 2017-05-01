C++=g++ -D__cfront21 -I. -I./inc

C++FLAGS= 

.o:
	$(C++) $(C++FLAGS) -c $*.cc

OBJS = \
 editor.o\
 List.o\
 maze.o\
 creational.o\
 abfactory.o\
 builder.o\
 factorymeth.o\
 prototype.o\
 singleton.o\
 adapter.o\
 bridge.o\
 decorator.o\
 facade.o\
 flyweight.o\
 proxy.o\
 chain.o\
 command.o\
 interpreter.o\
 iterator.o\
 mediator.o\
 memento.o\
 observer.o\
 state.o\
 strategy.o\
 visitor.o 

target:	$(OBJS)

scenario.o: scenario.cc
	$(C++) $(C++FLAGS) -c $*.cc
	$(C++) $(C++FLAGS) -c -DSpell1 $*.cc  

foundation.o: foundation.cc
	$(C++) $(C++FLAGS) -c $*.cc

creational.o: creational.cc

maze.o: maze.cc
	$(C++) $(C++FLAGS) -c $*.cc  
	$(C++) $(C++FLAGS) -DSingleton=1 -c $*.cc  

abfactory.o: abfactory.cc

builder.o: builder.cc

factorymeth.o: factorymeth.cc
	$(C++) $(C++FLAGS) -DImplementation1=1 -c $*.cc
	$(C++) $(C++FLAGS) -DImplementation2=1 -c $*.cc
	$(C++) $(C++FLAGS) -DImplementation3=1 -c $*.cc

prototype.o: prototype.cc
	$(C++) $(C++FLAGS) -DSampleCode1=1 -c $*.cc
	$(C++) $(C++FLAGS) -DSampleCode2=1 -c $*.cc

singleton.o: singleton.cc
	$(C++) $(C++FLAGS) -DImplementation1=1 -c $*.cc
	$(C++) $(C++FLAGS) -DImplementation2=1 -c $*.cc

adapter.o: adapter.cc  

composite.o: composite.cc

decorator.o: decorator.cc

facade.o: facade.cc

flyweight.o: flyweight.cc

proxy.o: proxy.cc
	$(C++) $(C++FLAGS) -DImplementation=1 -c $*.cc
	$(C++) $(C++FLAGS) -DSampleCode=1 -c $*.cc

chain.o: chain.cc
	$(C++) $(C++FLAGS) -DImplementation=1 -c $*.cc
	$(C++) $(C++FLAGS) -DSampleCode=1 -c $*.cc

command.o: command.cc
interpreter.o: interpreter.cc
iterator.o: iterator.cc
mediator.o: mediator.cc
memento.o: memento.cc
observer.o: observer.cc
state.o: TCPClosed.cc state.cc

strategy.o: strategy.cc
	$(C++) $(C++FLAGS) -DConsequences1=1 -c $*.cc
	$(C++) $(C++FLAGS) -DConsequences2=1 -c $*.cc
	$(C++) $(C++FLAGS) -DImplementation=1 -c $*.cc
	$(C++) $(C++FLAGS) -DSampleCode=1 -c $*.cc

visitor.o: visitor.cc
	$(C++) $(C++FLAGS) -DConsequences=1 -c $*.cc
	$(C++) $(C++FLAGS) -DImplementation=1 -c $*.cc
	$(C++) $(C++FLAGS) -DSampleCode=1 -c $*.cc
