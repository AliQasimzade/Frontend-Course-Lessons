# HTTP Nədir ?

<p>HTTP-in açılışı - HyperText Transfer Protocoldur və http qlobal şəbəkənin (www) əsasını təşkil edən və 1990-cı ildən istifadə olunan şəbəkə protokoludur. Bu protokol sayəsində internetdəki veb səhifələrə baxmaq olar. O, kompüter (klient) ilə server (server) arasında əlaqəni təmin edir və alış-veriş qaydalarını müəyyən edir. Port kimi port 80-dən istifadə edir.</p>

# HTTP necə işləyir ?
<p>Gün ərzində bəlkə də onlarla müxtəlif veb-saytlara göz gəzdiririk. Bu veb-saytlara daxil olarkən kompüterimiz serverə sorğular göndərir. Burada http protokolu müdaxilə edir və kompüterimizlə serverlər arasında körpü rolunu oynayır. Biz bütün bu əməliyyatları Google Chrome və Firefox kimi brauzerlər vasitəsilə edirik.



![alt text](https://miro.medium.com/max/853/1*MoxFEabKGx6NxlKoZ0lXJQ.png)
</p>

## HTTP status kodlari

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