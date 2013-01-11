# afck
## What is this program?
This program is a simple attempt at fixing broken world files from the educational program Alice. Alice will occasionally, due to a long standing bug, break it's own save files in such a way that prevents them from being opened in Alice. Usually Alice returns an error like this:
```
Unable to load world

Alice version: 2.3
os.name: Windows 7
os.version: 6.1
os.arch: x86
java.vm.name: Java HotSpot(TM) Client VM
java.vm.version: 20.0-b11
user.dir: C:\Program Files\Alice2.3\Alice 2.3\Required

Throwable that caused the error:
edu.cmu.cs.stage3.alice.core.IllegalNameValueException: Unfortunately, something else in this world is already named "index," so you can't use that name here.
  at edu.cmu.cs.stage3.alice.core.Element.checkForNameCollision(Element.java:221)
	at edu.cmu.cs.stage3.alice.core.Element.internalSetParent(Element.java:680)
	at edu.cmu.cs.stage3.alice.core.Element.insertChildAt(Element.java:1050)
	at edu.cmu.cs.stage3.alice.core.Element.addChild(Element.java:1058)
	at edu.cmu.cs.stage3.alice.core.Element.setParent(Element.java:641)
	at edu.cmu.cs.stage3.alice.core.response.LoopNInOrder.loadCompleted(LoopNInOrder.java:59)
	at edu.cmu.cs.stage3.alice.core.Element.loadCompleted(Element.java:1429)
	at edu.cmu.cs.stage3.alice.core.Element.loadCompleted(Element.java:1429)
	at edu.cmu.cs.stage3.alice.core.Element.loadCompleted(Element.java:1429)
	at edu.cmu.cs.stage3.alice.core.Element.load(Element.java:1559)
	at edu.cmu.cs.stage3.alice.authoringtool.dialog.LoadElementProgressPane.construct(LoadElementProgressPane.java:42)
	at edu.cmu.cs.stage3.progress.ProgressPane$2.run(ProgressPane.java:86)
	at java.lang.Thread.run(Thread.java:662)
```
This program is intended to fix Alice files with this issue


## How is it done?
_Coming soon!_


## What does afck stand for?
Alice File ChecK (a play on fsck, the well-known filesystem checking and repair tool.)
