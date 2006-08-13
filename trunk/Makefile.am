
EXEEXT=

pyui_files= documentdetails.py

%.py : %.ui
	pyuic $< >$@


bin_PROGRAMS = podkatcher
podkatcher_SOURCES = podkatcher.py documentdetails.ui

podkatcher$(EXEEXT): $(pyui_files)
	echo "Done"
