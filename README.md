# DeepVision_Online-idea
DeepVision'ın online çalışması için geliştirilen uygulama:


//////////////////////////////////////////////////////////////


	DeepVision MSI'da çalıştırma komutları şu şekildedir. Sharepoint DeepVision içinde ekran görüntüleri dosyası içide ayrıca ekran goruntüsünü paylaştığım dizinde :
	python manage.py runserver IP komutunu çağırarak çalıştırılıyor. Ekran görüntüsü yine belirtilen dosyadadır.

	IP bilgisini değiştirmek istediğinizde ise mysite dosyası içinde şu kısımlarda değişiklik yapmanız gerekli :
	settings.py içinde allowed host kısmına eklemek istediğiniz IP girişi yapılmalı onu da ekte paylaşıyorum.

	Ayrıca yine mysite dosyasında views.py dosyasında darknet in çalışması için gerekli komut ve resim path i eklenmiştir, değiştirilebilir.

	Mysite içinde index.html dosyasında servise (Postman üzerinden deneylemiştik) ilgili IP de tahmin için gönderilen resim vardır

	Eğitim için kullanılan eğitim verileri uygulama içinde /home/vision/Music/darknet/newLabeledData dosyasında buluyor olup üzenli etiketi veri sharepointe yüklenmiştir.
	Ayrıca /home/vision/Music/darknet/cfg içinde ilgili sınıf isimleri yer almaktadır.

	Yine cfg  içinde tuborg.data dosyasında eğer eğitim ve test verilerinin path i değiştiyse veya sınıfa sayısı değiştiyse değiştirilmesi gerek. Backup eğitim sırasında kaydedilen modelin tutulduğu klasör path i dir bu dosya içinde. Validation kümesi dummy tutulmuştur.

	Ayrıca /home/vision/Music/darknet/src içide image.c dosyası içinde detection outupu servis için güncellenmiştir.

	Bu uygulama Draknet kütüphanesi kullanarak yolov3 versiyonu üzerinden geliştirilmiştir.
	Çalışma sırasında demo ekranları ve terminal üzerinden çalışma deneylerinin zaman zaman alınan ekran görüntüleri sharepoint!e yüklenmiştir.

	Son olarak projenin githuba yüklenmesi birazdan tamamlanacaktır. Uygulma MSI RTX 2070 ekran kartı ve 8 GB lik bir ekran kullanımıyla geliştirilmiştir.

///////////////////////////////////////////////////////////////
