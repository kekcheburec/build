# Armbian с патчем PREEMPT RT для ядра v4.19.72 #

**Сборка**

	apt-get -y install git
	git clone https://github.com/kekcheburec/build
	cd build
	./compile.sh docker BOARD="nanopineo" RELEASE="stretch"
