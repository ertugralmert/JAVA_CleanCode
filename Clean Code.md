# Clean Code

1. Kodlarınız temiz açık ve anlaşılır şekilde yazılmalıdır. (clean code). Kodunuzdan kötü kokular gelmemelidir. (code smell)
2. Sınıflarımızı OOP nin  genel kuralları çerçevesinde soyutlayarak oluştururuz. Ancak bu soyutlamalar da dikkat etmemiz gereken kuralların başında her bir görev atfedilen eylemin tek bir iş yapmasını sağlamalısınız. Yani bir sınıf içinde bir method tanımlıyorsanız o method sadece bir görevi ifa etmelidir. Tek sorumluluk ilkesi (single responsibiliity)
3. Sınıf oluştururken belli görevleri yapmak üzere methodlar tanımlarız. Tanımlanan methodların sayısı bir sınıf için 10-15 aralığında kalmalı ve bu sayıyı aşmamalıdır.
4. Methodlar sadece tek bir iş yapmalılar demiştik, bunu kontrol etmenin en kolay yolu; eğer bir kodlamada copy-paste yapılıyorsa tekrar eden kodlar vardır ve tek görev ilkesine de uyulmuyordur.
5. Methodların içi kodlama yaptığımız ana kısımlardır. Bu neden bu kısımlar olabildiğinde anlaşılır olmalıdır. Methodun okunaklığını sağlamak için methodların satı sayılarını kısılatmak gereklidir. Bir method 15-20 satırdan fazla kodlanmamalıdır. Ayrıca bir method içinde tanımlanan değişken sayısı max 2 adetle kısıtlı kalmalıdır.
6. Methodlarda, akış belli koşullar oluştuğunda farklı yönlere sahiptir. Burada yazılımsal olarak koşul ifadeleri ile akışın yönünü yönetebiliriz. Ancak method içinde en fazla 7-8 koşul ifadesi kullanınız.
7. MEthodlarımız kodlayama başladığımızda küçüktürler ve genellikle öyle devam edebilirler. ancak zaman içinde gelen yeni case'ler ve farklı istekler neticesinde methodların içieriği fazla büyümeye başlar. İşte bu gibi durumlarda belli aralıklar ile kodlarımızı düzenlememiz, 5.madde belirtğim koşullara uyuncaya kadar küçültmeniz gerekecektir.
8. Bazen belli methodlar farklı işlemler yapıyor gibi görünselerde aynı işi yapabiliyorlar, ya ad kısmi olarak belli kod öbeklerini ortaklaşa kullanabiliyorlar. Bu neden ortak olan kod bloklarını tek bir method çatısında toplamak ve kullanmak doğru olacaktır.
9. Methodların iisimlendirilmesi, genellik methodların üstlendikleri görev, yapacakları iş ile doğru olacak şekilde isimlendirme yapmalıyız. Emir kipi kullanmak doğru bir yöntem olacaktır.
10. Methodların isimlendirirken elinizi korkak alıştırmayın. 🙂Java da sınırlama yoktur.
11. Eğer bir method a isim vermekte zorlanıyor iseniz, muhtemelen o method bir den çok iş yapıyordur ve isimlendirme zorlaşmıştır.
12. Kodların dökümante edilmesi ve readme yazmak. Öncelikle her method üzerine açıklama yazmalısınız. Değişkenlerin görevlerini methodun işlevini ve geri dönüş tipini açıklamasını methodun üzerinde mutlaka yazınız. Ayrıca kodlamalarınız ve gerekli uyarılan yer aldığı readme dosyası oluşturmakta bu işin bir parçasıdır.

\---

Temiz kod yazdığımızda kodlar küçük, anlaşılır ve test edilebilir olur.

Temiz kod, verimliliği arttırır.

Temiz kod, hata yapma oranını düşürür.

Temiz kod, kodun bakımını yapmak kolaydır.

Temiz kod, kodun anlaşılır ve yeniden kullanırlığını arttırır. Böylece başka projelerde de kod kullanılabilir.

