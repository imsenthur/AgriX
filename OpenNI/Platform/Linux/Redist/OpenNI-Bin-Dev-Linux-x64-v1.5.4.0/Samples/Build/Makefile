include Common/CommonDefs.mak

.PHONY: all

NETPROJ = 
ifneq "$(realpath /usr/bin/gmcs)" ""
endif

all: $(NETPROJ) NiSimpleRead NiConvertXToONI NiAudioSample NiSimpleSkeleton NiUserSelection NiCRead NiSimpleCreate NiHandTracker NiSampleModule NiUserTracker SimpleViewer.java NiRecordSynthetic NiSimpleViewer NiBackRecorder SimpleRead.java NiSkeletonBenchmark UserTracker.java NiViewer 


.PHONY: NiSimpleRead
NiSimpleRead:
	$(MAKE) -C ../NiSimpleRead

.PHONY: NiConvertXToONI
NiConvertXToONI:
	$(MAKE) -C ../NiConvertXToONI

.PHONY: NiAudioSample
NiAudioSample:
	$(MAKE) -C ../NiAudioSample

.PHONY: NiSimpleSkeleton
NiSimpleSkeleton:
	$(MAKE) -C ../NiSimpleSkeleton

.PHONY: NiUserSelection
NiUserSelection:
	$(MAKE) -C ../NiUserSelection

.PHONY: NiCRead
NiCRead:
	$(MAKE) -C ../NiCRead

.PHONY: NiSimpleCreate
NiSimpleCreate:
	$(MAKE) -C ../NiSimpleCreate

.PHONY: NiHandTracker
NiHandTracker:
	$(MAKE) -C ../NiHandTracker

.PHONY: NiSampleModule
NiSampleModule:
	$(MAKE) -C ../NiSampleModule

.PHONY: NiUserTracker
NiUserTracker:
	$(MAKE) -C ../NiUserTracker

.PHONY: SimpleViewer.java
SimpleViewer.java:
	$(MAKE) -C ../SimpleViewer.java

.PHONY: NiRecordSynthetic
NiRecordSynthetic:
	$(MAKE) -C ../NiRecordSynthetic

.PHONY: NiSimpleViewer
NiSimpleViewer:
	$(MAKE) -C ../NiSimpleViewer

.PHONY: NiBackRecorder
NiBackRecorder:
	$(MAKE) -C ../NiBackRecorder

.PHONY: SimpleRead.java
SimpleRead.java:
	$(MAKE) -C ../SimpleRead.java

.PHONY: NiSkeletonBenchmark
NiSkeletonBenchmark:
	$(MAKE) -C ../NiSkeletonBenchmark

.PHONY: UserTracker.java
UserTracker.java:
	$(MAKE) -C ../UserTracker.java

.PHONY: NiViewer
NiViewer:
	$(MAKE) -C ../NiViewer
