# Object Oriented Programming Kodluyoruz Patika.dev

Bu repo [Kodluyoruz](Kodluyoruz.org) Object Oriented Programming eğitimi için hazırlamış olduğum repo. İçerisinde Java Object Oriented Programming ödevlerinin soru ve cevaplarını içeren bir adet README dosyası barındırıyor.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

| ÖDEVLER |
|-----|
| [ÖDEV 1](https://github.com/Ramedeus/Object_Oriented_Programming_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-%C3%B6dev-1--%C3%BCniversite-y%C3%B6netim-sistemi) - Üniversite Yönetim Sistemi |
| [ÖDEV 2](https://github.com/Ramedeus/Object_Oriented_Programming_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-%C3%B6dev-2--hayvanat-bah%C3%A7esi-y%C3%B6netimi) - Hayvanat Bahçesi Yönetimi |
| [ÖDEV 3](https://github.com/Ramedeus/Object_Oriented_Programming_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-%C3%B6dev-3--u%C3%A7u%C5%9F-y%C3%B6netim-sistemi) - Uçuş Yönetim Sistemi |
| [ÖDEV 4](https://github.com/Ramedeus/Object_Oriented_Programming_Kodluyoruz_Patika.dev/blob/main/README.md#open_book-%C3%B6dev-3--u%C3%A7u%C5%9F-y%C3%B6netim-sistemi) - Online Film Sistemi |


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## :open_book: ÖDEV 1	- Üniversite Yönetim Sistemi

### SORU :question:

1 - Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.   
2 - Departmanlara ait ofisler vardır.   
3 - Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.   
4 - Her çalışan bir ofiste çalışır.   
Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.   

Not : Sınıflara ait nitelik ve davranışların belirtilmesine gerek yoktur.

### :green_square: CEVAP

<details>
<summary>Diyagramı görmek için tıklayınız.</summary>
    
<img src="https://github.com/Ramedeus/Logo/blob/main/%C3%9Cniversite%20Y%C3%B6netim%20Sistemi.PNG "/>
 
</details>


  
  
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  

## :open_book: ÖDEV 2	- Hayvanat Bahçesi Yönetimi

### SORU :question:

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

- Hayvanlar:   
Atlar (atlar, zebralar, eşekler vb.),   
Kedigiller (kaplanlar, aslanlar vb.),   
Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.   
- Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır. (tür adı, ağırlığı, yaşı vb.)   
- Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()   
- Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()   
- Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.   
   
Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

### :green_square: CEVAP

<details>
<summary>Diyagramı görmek için tıklayınız.</summary>
    
<img src="https://github.com/Ramedeus/Logo/blob/main/Hayvanat%20Bah%C3%A7esi%20Y%C3%B6netimi.PNG "/>
 
</details>

  
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  

## :open_book: ÖDEV 3	- Uçuş Yönetim Sistemi

### SORU :question:

Uçuşların ve pilotların yönetimi için bir sistem tasarlayın.

- Hava yolu şirketleri uçuşları gerçekleştirir. Her hava yolunun bir kimliği vardır.   
- Hava yolu şirketi, farklı tipteki uçaklara sahiptir.   
- Uçaklar çalışır veya onarım durumunda olabilir.   
- Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.   
- Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.   
- Havaalanlarının benzersiz kimlikleri ve isimleri vardır.   
- Hava yolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.   
- Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.   

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.   

### :green_square: CEVAP

<details>
<summary>Diyagramı görmek için tıklayınız.</summary>
    
<img src="https://github.com/Ramedeus/Logo/blob/main/U%C3%A7u%C5%9F%20Y%C3%B6netim%20Sistemi.PNG "/>
 
</details>

  
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------  

## :open_book: ÖDEV 4	- Online Film Sistemi

### SORU :question:

Online film satan veya kiralayan uygulamanın sistemini tasarlayın.

- Uygulamada filmler listelenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.   
- Kullanıcılar abonelik için sistem üzerinden kredi satın alır.   
- Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.   
- Normal kullanıcılar ve aboneler film satın alabilirler.   
- Eğer film mevcut değil ise talep edilebilir.   

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.

### :green_square: CEVAP

<details>
<summary>Diyagramı görmek için tıklayınız.</summary>
    
<img src="https://github.com/Ramedeus/Logo/blob/main/Online%20Film%20Sistemi.PNG "/>
 
</details>


  
  
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

  
## Contributing :hammer_and_wrench:	
Hatalar, öneriler ve değişiklikler için lütfen bir konu açınız.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

## License :notebook_with_decorative_cover:

[MIT](https://www.google.com/search?q=mit+license&oq=mit+license&aqs=chrome.0.0l4j0i22i30l6.2910j0j7&sourceid=chrome&ie=UTF-8)
  
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- 

<img src="https://github.com/Ramedeus/Logo/blob/main/Ramedeus2.png " width="300" height="300"/>
