# F5-BIG-IP-Cookie-Encoder

Web sunucuları F5 BIGIP yük dengeleme cihazları arkasına ise, F5 cihazı kullanıcıya bir tanımlama bilgisi(Cookie) atayarak, aynı kullanıcının sonraki isteklerini içerideki ilgili web sunucusuna yönlendirmektedir.
F5 tarafından atanan bu Cookie değeri, bilinen bir algoritmayla kodlandığından, aynı kodlama yöntemi tersine uygulanarak F5 arkasındaki web sunucusunun gerçek IP adresini ve web sunucu port numarasını öğrenmek mümkün olabilmektedir. 
F5 cihazı arkasındaki web sunucusu Internet üzerinden ulaşılabilir bir IP adresine sahipse, bu durum DoS saldırılarında F5’i egale edip direk arkadaki web sunucusuna saldırma amaçlı kullanılabilir. Veya yapılan denetimler sırasında F5’in aradan çıkartılmasına ve direk hedef sistemin denetlenmesine imkan sağlar.

Daha fazla bilgi için  :

http://www.sertankolat.com/2011/12/f5-big-ip-cookie-tespiti-ve-desifreleme.html

# Kullanımı

python f5-cookie-encoding ip_adresi port

