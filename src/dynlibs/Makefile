
all:
	$(MAKE) -C mgd
	$(MAKE) -C mgdbm
	$(MAKE) -C mpq
	$(MAKE) -C mmysql
	$(MAKE) -C mregex
	$(MAKE) -C msocket
	$(MAKE) -C munix

install:
	$(MAKE) -C mgd install
	$(MAKE) -C mgdbm install
	$(MAKE) -C mpq install
	$(MAKE) -C mmysql install
	$(MAKE) -C mregex install
	$(MAKE) -C msocket install
	$(MAKE) -C munix install

test:
	$(MAKE) -C mgd test
	$(MAKE) -C mgdbm test
	$(MAKE) -C mpq test
	$(MAKE) -C mmysql test
	$(MAKE) -C mregex test
	$(MAKE) -C munix test

clean:
	$(MAKE) -C msocket test
	$(MAKE) -C mgd test
	$(MAKE) -C mgdbm test
	$(MAKE) -C mpq test
	$(MAKE) -C mmysql test
	$(MAKE) -C mregex test
	$(MAKE) -C munix test
