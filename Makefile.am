ACLOCAL_AMFLAGS = -I m4

SUBDIRS = \
	aihdcontroler \
	antiscrollbar \
	ardmediathek \
	audiosync \
	automaticcleanup \
	automaticvolumeadjustment \
	autoresolution \
	autotimer \
	babelzapper \
	blindscan \
	bonjour \
	cdinfo \
	dreamexplorer \
	dreamirc \
	dreammediathek \
	dvdbackup \
	dyndns \
	easyinfo \
	easymedia \
	eibox \
	elektro \
	emailclient \
	epgrefresh \
	epgsearch \
	fancontrol2 \
	filebrowser \
	fritzcall \
	fstabeditor \
	ftpbrowser \
	growlee \
	httpproxy \
	imdb \
	kiddytimer \
	letterbox \
	logomanager \
	mediadownloader \
	merlinepg \
	merlinepgcenter \
	merlinmusicplayer \
	mosaic \
	moviecut \
	movieretitle \
	movietagger \
	mphelp \
	multirc \
	ncidclient \
	netcaster \
	networkbrowser \
	netzkino \
	ofdb \
	orfat \
	orfteletext \
	partnerbox \
	permanentclock \
	porncenter \
	primetimemanager \
	reconstructapsc \
	recordinfobar \
	satipclient \
	seekbar \
	setpasswd \
	shoutcast \
	showclock \
	simplerss \
	svdrp \
	systemtime \
	tageditor \
	trafficinfo \
	transcodingsetup \
	transmission \
	tvcharts \
	unwetterinfo \
	valixdcontrol \
	virtualzap \
	vlcplayer \
	vps \
	vfdcontrol \
	webcamviewer \
	werbezapper \
	zapstatistic \
	zdfmediathek

metadir = $(datadir)/meta
meta_DATA = index-enigma2-plugins.xml
CLEANFILES = index-enigma2-plugins.xml

index-enigma2-plugins.xml: $(top_srcdir)/genmetaindex.py $(top_srcdir)/*/meta/plugin_*.xml
	$(AM_V_GEN)$(PYTHON) $^ > $@
