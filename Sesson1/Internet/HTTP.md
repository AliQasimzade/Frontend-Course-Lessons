# HTTP Nədir ?

<p>HTTP-in açılışı - HyperText Transfer Protocoldur və http qlobal şəbəkənin (www) əsasını təşkil edən və 1990-cı ildən istifadə olunan şəbəkə protokoludur. Bu protokol sayəsində internetdəki veb səhifələrə baxmaq olar. O, kompüter (klient) ilə server (server) arasında əlaqəni təmin edir və alış-veriş qaydalarını müəyyən edir. Port kimi port 80-dən istifadə edir.</p>

# HTTP necə işləyir ?
<p>Gün ərzində bəlkə də onlarla müxtəlif veb-saytlara göz gəzdiririk. Bu veb-saytlara daxil olarkən kompüterimiz serverə sorğular göndərir. Burada http protokolu müdaxilə edir və kompüterimizlə serverlər arasında körpü rolunu oynayır. Biz bütün bu əməliyyatları Google Chrome və Firefox kimi brauzerlər vasitəsilə edirik.



![alt text](https://miro.medium.com/max/853/1*MoxFEabKGx6NxlKoZ0lXJQ.png)
</p>

## HTTP status kodlari
> xx status kodlarında kı, rəqəmi bildir (01,10 20) kimi.
* 1xx Məlumat
* 2xx Uğur
* 3xx Yönləndirmə
* 4xx Brauzer Xətası
* 5xx Server Xətası

<p>İndi status kodlarına ətraflı baxaq.</p>

| Status kodu | Mesaj | Məna|
| :---         |     :---:      |          ---: |
| **1xx**   | **Məlumat**    |    |
| 100    | Davam et      | Davam et     |
| 101    | Kommutasiya Protokolları      | Kommutasiya Protokolu     |
| 102    | Emal edilir      | Proses     |
| **2xx**    |**Uğur**     | Davam et     |
| 200    | tamam      | tamam    |
| 201    | yaradılmışdır      | yaradılmışdır    |
| 202    | Qəbul edildi      | Təsdiq edildi     |
| 203    | Səlahiyyətli olmayan məlumat     | Qeyri-kafi məlumat     |
| 204    | Məzmun yoxdur      | Məzmun yoxdur     |
| 205    | Məzmunu Sıfırlayın     | Məzmunu Sıfırlayın     |
| 206    | Qismən Məzmun     | Qismən Məzmun    |
| 207    | Çox statuslu      | Çox statuslu    |
| 210    | Məzmun Fərqlidir      | Fərqli Məzmun    |
| **3xx**    | **Orientasiya**      |     |
| 300    | Çoxsaylı Seçimlər      | Çoxlu seçimlər    |
| 301    | Daimi Köçürüldü     | Daimi köçürülüb    |
| 302    |Müvəqqəti olaraq köçürülüb| Müvəqqəti Köçürüldü |
| 303    | Digərlərinə baxın      | Başqalarına baxın    |
| 304    | Dəyişdirilməmişdir     | Kvalifikasiya edilə bilmədi|
| 305    | Proxy istifadə edin     | Proksi istifadə edin|
| 307    | Müvəqqəti yönləndirmə    | Müvəqqəti olaraq yenidən göndərin|
| **4xx**    | **Skaner xətası**    | |
| 400    | Səhv İstək   | Pis Arzu  |
| 401    | İcazəsiz     | İcazəsiz    |
| 402    | Ödəniş Tələb olunur    | Ödəniş Tələb olunur |
| 403    | Qadağan    | Qadağandır |
| 404    | Tapılmadı    | Səhifə tapılmadı    |
| 405    |İcazəsiz Metod    | İcazəsiz Metod |
| 406    | Qəbuledilməz     | Qəbuledilməz    |
| 407    |Proksi Serverə daxil olmaq tələb olunur| Proksi Serverə daxil olmaq tələb olunur  |
| 408    | Sorğunun vaxtı bitdi    | Sorğunun vaxtı bitdi    |
| 409    | Münaqişə  | (Xətlər) Münaqişə, Münaqişə|
| 410    | 	Getdi |	Getdi|
| 411    | Uzunluq Tələb olunur | Uzunluq Tələb olunur|
| 412    | İlkin şərt alınmadı  |İlkin şərt alınmadı|
| 413    |Sorğu Müəssisəsi Çox Böyükdür| Sorğu Müəssisəsi Çox Böyükdür|
| 414    | Sorğu-URI çox uzun | Sorğu-URI çox uzun|
| 415    | Dəstəklənməyən Media Növü| Dəstəklənməyən Media Növü|
| 416    |Tələb olunan diapazon təmin edilmir|Tələb olunan diapazon təmin edilmir|
| 417    |Gözlənti uğursuz oldu |Gözlənti uğursuz oldu|
| 422    | Emal olunmayan varlıq| Emal olunmayan varlıq|
| 423    | Bağlanıb | Bağlanıb|
| 424    | Metodun uğursuzluğu | Metodun uğursuzluğu|
| **5xx**   | **Server xətası**| |
| 500    | Daxili Server Xətası| Daxili Server Xətası|
| 501    | Tətbiq edilməyib| Tətbiq edilməyib|
| 502    |Yanlış Gateway     | Yanlış Gateway   |
| 503    | Xidmət yoxdur | Xidmət yoxdur|
| 504    | Gateway Timeout |Gateway Timeout|
| 505    | HTTP Versiyası dəstəklənmir| HTTP Versiyası dəstəklənmir|





# HTTPS nədir ?

<p>HTTPS Hypertext Transfer Protocol Secure sözünün qısaldılmasıdır. HTTP kimi, onun da əsas məqsədi verilənləri serverdən brauzerinizə ötürməkdir, beləliklə vebsaytları yükləyə bilərsiniz. 

Bununla belə, HTTPS server və brauzer arasında əlaqə yaratmaq üçün şifrələnmiş bağlantıdan istifadə edir. SSL (təhlükəsiz yuva təbəqəsi) sertifikatı ötürülən məlumatların mübadilə zamanı oğurlanmasından qoruyur. 

HTTPS 1994-cü ildə yaradılıb, lakin 2019-cu ilə qədər standart kimi geniş istifadə olunmayıb. Onun populyarlığı əsasən Google-un saytların 2014-cü ildə HTTPS-ə keçməsini tövsiyə etməsi ilə bağlıdır . 

Siz həmçinin brauzerinizin ünvan çubuğunda HTTPS-i görə bilərsiniz (məsələn, https://www.semrush.com )</p>

# HTTP və HTTPS arasındakı fərq nədir?

<p>Şifrələnmiş bağlantısı sayəsində HTTPS HTTP-dən daha təhlükəsizdir. 

E-ticarət saytınız və ya həssas məlumatları idarə edən vebsaytınız olmasa belə saytın təhlükəsizliyi vacibdir. Təhlükəsiz sayt müştərilərinizi məlumatlarının oğurlanmasından qoruyur və veb saytınızı düzəltmək üçün vaxt və pul tələb edən təhlükəsizlik pozuntularından qoruyur. 

Digər üstünlüklərə aşağıdakılar daxildir:</p>

 1. **İstifadəçilər HTTPS-ə etibar edirlər:** Əlavə təhlükəsizlik istifadəçiləri brendinizə və vebsaytınıza etibar etməyə təşviq edir. Həssas məlumatları sizinlə paylaşarkən və ya veb saytınızda alış-veriş edərkən onlar özlərini daha rahat hiss edəcəklər.
 2. **SEO Reytinqini Artırın:** HTTPS interneti istifadəçilər üçün daha təhlükəsiz və daha yaxşı etdiyindən, Google 2014-cü ildə HTTP-dən HTTPS-ə keçidin böyük tərəfdarı idi. Onlar həmçinin HTTPS-dən istifadə edən veb-saytların HTTP-dən istifadə edənlərdən daha yüksək sıralanma potensialına malik olduğunu təsdiqlədilər.
