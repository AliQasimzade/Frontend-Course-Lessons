# DNS nədir?

<p>DNS (Domain Name System) verilənlər bazasıdır. İnternetdəki bir çox cihazı bir IP ünvanına uyğunlaşdırmağa kömək edir. Veb-saytı URL kimi daxil etdiyiniz zaman (məsələn, “google.com”) kompüteriniz DNS serverinə qoşulur. Daha sonra IP ünvanı olan səhifəyə yönləndirilir (məsələn, “172.217.23.110”). Bu yolla siz internet saytlarına IP ünvanları ilə deyil, yadda saxlamaq asan olan domen adları ilə daxil ola bilərsiniz.</p>

## DNS necə işləyir ?
<p>
DNS domen adlarını IP ünvanlarına çevirmək üçün verilənlər bazasına əsaslanır. Bu verilənlər bazası İnternetdəki bütün cihazların IP ünvanlarını və domen adlarını ehtiva edir.

İstifadəçi vebsayta URL kimi daxil olduqda (məsələn, “google.com”) kompüteriniz DNS serverinə qoşulur. DNS serveri sorğu edilən domen adının IP ünvanına yönləndirməni həyata keçirir. Bu proses aşağıdakı kimidir:

1. İstifadəçinin kompüteri DNS serverinə domen adı sorğusu göndərir.
2. DNS server verilənlər bazasında sorğu edilən domen adının IP ünvanını axtarır.
3. Əgər domen adı verilənlər bazasında varsa, DNS server IP ünvanını istifadəçinin kompüterinə göndərir.
4. İstifadəçinin kompüteri IP ünvanı ilə yönləndirilir və vebsayta daxil olur.
5. Əgər domen adı verilənlər bazasında mövcud deyilsə, DNS server domen adının qeydiyyatdan keçdiyi yüksək səviyyəli DNS serverinə sorğu göndərir (məsələn, “.com” uzantılı domen adı üçün “com” serveri). Bu yüksək səviyyəli DNS serveri domen adının qeydiyyatdan keçdiyi aşağı səviyyəli DNS serverini sorğulayır. Bu proses domen adının IP ünvanına çatana qədər davam edir.</p>

## DNS Tarixçəsi

<blockquote>DNS (Domain Name System) internetin ilk illərində ortaya çıxan bir sistemdir. İlk dəfə 1983-cü ildə ARPANET adlı şəbəkədə istifadə edilmişdir. O dövrdə internetdəki bütün qurğular bir-birinə IP ünvanları ilə qoşulurdu. Lakin bu ünvanlar uzun və qarışıq olduğundan onları yadda saxlamaq çətin olardı. Buna görə də daha asan yadda qalan domen adlarından istifadə etmək zərurəti yarandı.</blockquote>