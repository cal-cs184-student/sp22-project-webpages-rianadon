PROJDIR=../../../../p3-1-pathtracer-sp22-sweater_pt3
PATHTRACER=$(PROJDIR)/build/pathtracer

IMAGES=bunny-h.png bunny-l.png bunny-g.png spheres-h.png spheres-l.png spheres-g.png bench-h.png bench-l.png bench-g.png dragon-g.png bunny-1.png bunny-4.png bunny-16.png bunny-64.png bunny-d0.png bunny-d1.png bunny-d2.png bunny-d3.png bunny-d100.png bunny-s1.png bunny-s2.png bunny-s4.png bunny-s8.png bunny-s16.png bunny-s64.png bunny-s1024.png

TRACE = $(PATHTRACER) -t 8 -r 480 360

all: $(IMAGES)

clean:
	rm $(IMAGES)

bunny-h.png:
	$(TRACE) -s 64 -l 32 -m 1 -H -f $@  $(PROJDIR)/dae/sky/CBbunny.dae
bunny-l.png:
	$(TRACE) -s 64 -l 32 -m 1 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-g.png:
	$(TRACE) -s 64 -l 32 -m 5 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
spheres-h.png:
	$(TRACE) -s 64 -l 32 -m 1 -H -f $@ $(PROJDIR)/dae/sky/CBspheres_lambertian.dae
spheres-g.png:
	$(TRACE) -s 64 -l 32 -m 5 -H -f $@ $(PROJDIR)/dae/sky/CBspheres_lambertian.dae
spheres-l.png:
	$(TRACE) -s 64 -l 32 -m 1 -f $@ $(PROJDIR)/dae/sky/CBspheres_lambertian.dae
bench-h.png:
	$(TRACE) -s 64 -l 32 -m 1 -H -f $@ $(PROJDIR)/dae/sky/bench.dae
bench-l.png:
	$(TRACE) -s 64 -l 32 -m 1 -f $@ $(PROJDIR)/dae/sky/bench.dae
bench-g.png:
	$(TRACE) -s 64 -l 32 -m 5 -f $@ $(PROJDIR)/dae/sky/bench.dae
dragon-g.png:
	$(TRACE) -s 64 -l 32 -m 5 -f $@ $(PROJDIR)/dae/sky/dragon.dae

bunny-1.png:
	$(TRACE) -s 1 -l 1 -m 1 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-4.png:
	$(TRACE) -s 1 -l 4 -m 1 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-16.png:
	$(TRACE) -s 1 -l 16 -m 1 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-64.png:
	$(TRACE) -s 1 -l 64 -m 1 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae

bunny-d0.png:
	$(TRACE) -s 1024 -l 16 -m 0 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-d1.png:
	$(TRACE) -s 1024 -l 16 -m 1 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-d2.png:
	$(TRACE) -s 1024 -l 16 -m 2 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-d3.png:
	$(TRACE) -s 1024 -l 16 -m 3 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-d100.png:
	$(TRACE) -s 1024 -l 16 -m 100 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae

bunny-s1.png:
	$(TRACE) -s 1 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-s2.png:
	$(TRACE) -s 2 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-s4.png:
	$(TRACE) -s 8 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-s8.png:
	$(TRACE) -s 8 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-s16.png:
	$(TRACE) -s 16 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-s64.png:
	$(TRACE) -s 64 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
bunny-s1024.png:
	$(TRACE) -s 1024 -l 4 -m 4 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae

bunny-indirect.png:
	$(TRACE) -s 64 -l 32 -m 5 -f $@ $(PROJDIR)/dae/sky/CBbunny.dae
