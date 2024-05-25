# Machine Learning Based Attack Detection on Networks

Gelişen bilişim teknolojileri, dünya nüfusunun %63'ünü internet kullanıcısı yaparak hayatı kolaylaştırmış ve özgürleştirmiştir. Ancak, bu artan kullanım beraberinde bilgi ve bilgisayar güvenliği risklerini getirmiştir. İnternet, kötü niyetli kullanıcılar ve saldırganlar tarafından hedef haline getirilerek izinsiz girişlere maruz kalmaktadır. Bu izinsiz girişler, sistemlerin işlevsiz hale gelmesine, veri hırsızlığına ve donanım zararlarına yol açabilir. Bu tür saldırıları önlemek için çeşitli yöntemler kullanılmaktadır, bunlar arasında saldırı tespit sistemleri, antivirüsler, web filtreleme çözümleri ve güçlü kimlik doğrulama yöntemleri bulunmaktadır.

 

Deneysel sonuçların gerçekliği ve uygulanabilirliği açısından kullanılan veri kümesi çok önemlidir. Veriler ne kadar gerçekçi olursa sistemin uygulanabilirlik ve kıyaslanabilmeleri o kadar fazla olur. Bu sebeple literatürde sıkça kullanılan KDD Cup 99 veri kümesi tercih edilmiştir. Bu veri kümesi günümüzde saldırı tespitinde güncel olarak kullanılmaya devam edilmektedir. KDD Cup 99 veri seti, basit, içerik, zaman tabanlı trafik ve host tabanlı trafik adı altında 4 farklı gruptan, 41 özellik, toplam 494.021 kayıttan oluşmaktadır. KDD ve DARPA veri seti Amerikan Hava Kuvvetleri (US Air Force) network ağına benzer bir yapıya sahip olması düşünülerek tasarlanmış, bir benzetim veri setidir. KDD Cup 99 ve DARPA veri seti saldırı
tespit çalışmalarında en çok tercih edilen veri setlerindendir. 

  

Snıflandırma, verinin niteliklerine göre etiketlenmesini sağlar. Kullanılan veri kümesinin 42. sütunu olan çıkış verilerimizin normal ya da anormal şeklinde sınıflandırma yapacağımız veriler mevcuttur. Saldırı Tespit Sistemi’nin temel işlevi, saldırı ya da değil şeklinde bir analiz yapmaktır. Literatürde analiz hesabı yapan birçok sınıflandırma algoritması mevcuttur. Naive Bayes (NB), Decision Tree (DT), Random Forest (RF), Support Vector Machine (SVM),Logistic Regression (LR), Gradient Descent (GD) ve K-Nearest Neighbor (KNN) gibi birçok sınıflandırma yöntemi ve algoritmaları mevcuttur. Bu çalışmada seçilen veri kümesine en uygun ve en etkili sınıflandırma yönteminin hangisi olduğunu öğrenmek için Naive Bayes(NB), Decision Tree (DT), Random Forest (RF), Support Vector Machine (SVM),Logistic Regression (LR), Gradient Descent (GD) ve K-Nearest Neighbor (KNN) yöntemleri incelenmiştir.



Gerçekleştirilen çalışmada performans değerlendirilirken confusion (karşılık) matrix kullanılmıştır. Sınıflandırma algoritmaları performans değerlendirmesi yaparken sadece doğruluk oranına bakılması çalışma sonuçlarının objektif değerlendirilmesini engelleyecektir. Doğruluk oranına ek olarak duyarlılık (recall), kesinlik (precision) değerlerine de bakılması büyük önem arz etmektedir.



# SONUÇLAR: 
  
Sınıflandırma yöntemlerinden Naive Bayes, Decision Tree, Random Forest, Support Vector Machines, Logistic Regression, Gradient Descent, K-Nearest Neighbor yöntemleri kullanılarak sınıflandırma başarı oranları kıyaslanmıştır. Yapılan kıyaslamalar neticesinde en yüksek başarı oranı Random Forest algoritması ile %99.9882 başarım oranı elde edilmiştir. Ayrıca seçmiş olduğumuz veri setinin önişlemeden geçirildikten sonra düzenli dağılım gösteren veri seti olduğu görülmüştür. Ayrıca birçok uygulamada çok başarılı bir sınıflandırma yöntemi olan Naive Bayes bu çalışmada çok düşük başarım göstermiştir. Bu durum, uygulama alanına göre algoritma seçiminin ne denli önemli olduğunu göstermiştir. K-Nearest Neighbor yönteminin doğruluk, duyarlılık, kesinlik ve F1 Score değerleri ne kadar yüksek olsa da çalışma süresinin fazla olması bir dezavantaj olmuştur. Klasik makine öğrenmesi yöntemleri çokça irdelenip araştırma alanı bulmuştur. Günümüzde derin öğrenme yöntemleri gibi popüler yöntemler de mevcuttur. Derin öğrenme yöntemlerinin klasik makine öğrenmesi yöntemlerine göre çok daha fazla donanıma bağlılık dezavantajları bulunmaktadır. Ayrıca saldırı tespit sistemlerinde derin öğrenme yöntemleri ile yakalanan başarı oranları klasik makine öğrenmesi yöntemleri kadar başarılı olamamıştır.
