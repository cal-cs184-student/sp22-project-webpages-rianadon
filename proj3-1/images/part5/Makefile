PROJDIR=../../../../p3-1-pathtracer-sp22-sweater_pt3
PATHTRACER=$(PROJDIR)/build/pathtracer

IMAGES=bunny.png samplerate.png

TRACE = $(PATHTRACER) -t 8 -r 480 360

all: $(IMAGES)

clean:
	rm $(IMAGES)

bunny.png:
	$(TRACE) -s 2048 -a 64 0.05 -l 1 -m 5 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
samplerate.png: bunny.png
	mv bunny_rate.png samplerate.png
