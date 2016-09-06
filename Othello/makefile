JFLAGS = -g
JC = javac
.SUFFIXES: .java .class
.java.class:
	$(JC) $(JFLAGS) $*.java

CLASSES = \
        Node.java \
        OthelloMove.java \
        OthelloPlayer.java \
        OthelloRandomPlayer.java \
        OthelloState.java \
        Test.java \
        VPPlayer.java \
        VPPlayerMCTS.java \

default: classes

classes: $(CLASSES:.java=.class)

clean:
	$(RM) *.class