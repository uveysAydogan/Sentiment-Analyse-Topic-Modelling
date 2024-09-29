Belli bir tarih aralığında Twitter'dan çekilmiş olan 30k adet deprem il ilgili tweetin  duygu analizi yapılmaktadır. 
Burada tweetlerin çoğu incelenip konu üzerine araştırma yapıldıktan sonra 3 adet konukategorisi belirleir.
Bu 3 kategoriden toplam 500 adet tweet excelde el ile 1 ve 0 olarak etiketlenir(learningTweets.xlsx).
Bu topic modelleme işleminden sonra ml algoritmaları ile sınıflandırma işlemleri yapılıp, accuracy değerine göre en performanslı algoritma tespit edilir
Daha sonra tüm temizlenmiş tweetler, belirlenen kategoriler doğrutusunda sınıflandırılır.
Bu sınıflandırma işleminden sonra huggingface sitesinden Türkçe dili için geliştirilmiş duygu analizi modeli ile duygu analizi yapılır.
Günün sonunda  konular üzerine insanların duyguları keşfedilmiş olur.
Bu süreçte veriyi elden edip, ön işleyip, görslleştirene kadar tüm veri analizi ve makine öğrenmesi aşamaları uygulanmıştır.
