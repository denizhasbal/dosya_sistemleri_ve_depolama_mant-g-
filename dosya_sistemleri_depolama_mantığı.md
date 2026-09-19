# Dosya Sistemleri Ve Depolama Mantığı


##NFTS-ext4-APFS Nedir
  Bunlar dosya sistemleridir. Yani işletim sisteminin diskteki dosyaları nasıl saklayacağını ve yöneteceğini belirler
	
NFTS - windowsta yaygın
ext4 - linuxta yayhın
 APFS - apple cihazlarında (macOS,İphone/İpad)kullanılır
	  
kısaca:dosya sistemi= diskteki dosyaların nasıl düzenleneceğini belirler
	  
	  
##Blok Yapısı Nedir

 Diskteki alan,küçük parçalara ayrılır. Bu parçalara blok denir
	 örn: bir dosya 3 blok yer kaplayabilir
	 dosya - blok1+blok2+blok3
	 işletim sistemi dosyanın hangi bloklarda oldugunu takip eder
		   
		   
## HDD vs SDD Çalışma Prensipleri

  HDDnin içinde dönen manyetik diskler ve hareket eden bir okuma/yazma kafası bulunur
Veri okunurken kafa diskin üzerinde hareket eder ve ilgili bölgedeki veriyi okur
   Bu Yüzden:
		  hareketli parçaları vardır
				  daha yavaştır
				  darbelerden daha fazla etkilenebilir
				  
				  HDD = dönen disk + hareket eden kafa
				  
	SDD de hareket eden parça yoktur
	Veriler flash bellek çiplerinde saklanır
	   Bu Yüzden:
	             çok daha hızlıdır
				 sessizdir
				 mekanik parçası yoktur
				 darbelere karşı hdd den daha dayanıklıdır
				 
				 SDD = flash bellek + elektronik devreler
