# MOLEKULER-KUANTUM-FINAL
MOLEKÜLER KUANTUM  dersi final ödevi H2 molekülü HF enerjisi

Baz Seti ve Moleküler İntegraller:

Baz Seti (STO-3G):
 Bu, atomik orbitallerin nasıl temsil edileceğini belirleyen bir matematiksel fonksiyon kümesidir. Minimal baz seti olan STO-3G, her bir atomik orbital için üç Gauss fonksiyonu kullanır.

Örtüşme Matrisi (S):
 Bu matris, farklı atomik orbitallerin uzayda ne kadar örtüştüğünü gösterir. Örneğin, iki hidrojen atomunun 1s orbitalleri arasındaki örtüşmeyi gösterir.

Çekirdek Hamiltonian Matrisi (h):
 Bu matris, elektronların çekirdeklerle olan etkileşimlerini ve elektronların kinetik enerjilerini içerir.

Başlangıç Tahmini:
İlk adımda, hesaplamalarımıza başlamak için bir başlangıç tahmini yapmamız gerekiyor. Bu tahmin genellikle çekirdek Hamiltonian matrisini (h) kullanarak yapılır.

Yoğunluk Matrisi Hesaplaması:
İlk yoğunluk matrisini oluştururuz. Bu matris, elektronların molekül içindeki dağılımını gösterir.

Fock Matrisi Oluşturulması:
Fock matrisi, çekirdek Hamiltonian matrisini ve iki elektron integrallerini kullanarak oluşturulur. Bu matris, elektron-elektron etkileşimlerini ve elektronların çekirdeklerle olan etkileşimlerini içerir.

Roothaan Denklemlerinin Çözülmesi:
Fock matrisini kullanarak Roothaan denklemlerini çözeriz. Bu denklemler, moleküler orbital katsayılarını ve orbital enerjilerini verir.

Yoğunluk Matrisinin Güncellenmesi:
Yeni moleküler orbitalleri kullanarak yoğunluk matrisini güncelleriz. Bu adım, sistemdeki elektron dağılımını daha doğru bir şekilde yansıtır.

Öz-Uyumluluk Kontrolü:
Yeni yoğunluk matrisini eski matrisle karşılaştırarak yakınsama kontrolü yaparız. Eğer fark yeterince küçükse (10⁻⁴), hesaplamalar tamamlanır. Değilse, Fock matrisini yeniden hesaplayarak adımları tekrarlarız.

Enerji Hesaplaması:
Son adımda, toplam enerjiyi hesaplarız. Bu enerji, elektronların toplam enerjisi ve çekirdekler arası itme enerjisinin toplamıdır.
Anahtar Kavramlar

Öz-Uyumlu Alan (SCF) Yöntemi:
Bir çok elektronlu sistemin Schrödinger denklemini iteratif olarak çözen ve kararlı bir elektron yoğunluğu dağılımı elde etmeye çalışan bir yöntemdir.

Hartree-Fock (HF) Teorisi:
Bir kuantum çok cisim sisteminin dalga fonksiyonunu ve enerjisini yaklaşık olarak belirlemek için kullanılan bir ortalama alan yaklaşımıdır. Kısıtlamalı Hartree-Fock (RHF) yaklaşımı, zıt spinli elektronlar için orbitallerin aynı olmasını gerektirir.