# Lojistik Regresyon
Amac siniflandirma problemi icin bagimli ve bahimsiz degiskenler arasindaki iliskiyi tanimlayan dogrusal bir model kurmaktir.
-Bagimli degisken kategoriktir.
-Adini bagimli degiskene uygulanan logit donusumden alir.
-Dogrusal regresyonda aranan varsayimlarburada aranmadigi icin daha esnek kullanilabilirligi vardir.
-Bagimli degiskenin 1 olarak tanimlanan degerini gerceklesme olasiligi hesaplanir. Dolayisiyla bagimli degiskenin alacagi deger ile ilgilenilmez.
-Lojstik fonksiyonu sayesinde uretilen degerler 0-1 arasinda olur.

# Destek Vektor Makineleri - SVM
Amac iki sinif arasindaki ayrimin optimum olmasini saglayacak hiper-duzlemi bulmaktir.

Dogrusal Olmayan SVM'de grafigi 3 boyutluya cikartiyoruz. Kernell trick(hilesi) adi verilir.

# Yapay Sinir Aglari

# CART
Heterojen veri setleri belirlenmis bir hedef degiskene gore homojen alt gruplara ayrilir
Amac veri seti icersindeki karmasik yapilari basit karar yapilarina donusturmektir.

# Random Forests
Temeli birden cok karar agacin urettigi tahminlerin bir araya getirilerek degerlendirilmesine dayanir.
- Bagging
Temeli bootstrap yontemi ile olusturulan birden fazla karar agacinin urettigi tahminlerin bir araya getirilerek degerlendirilmesine dayanir.

# Gradient Boosting Machines
Adaboost'un genelleştirilmis versiyonudur.

Artiklar uzerine tek bir tahminsel model formunda olan modeller serisi kurulur.
GBM tek bir tahminsel model formunda olan modeller serisi olusturur.
Seri icerisindeki bir model serideki bir onceki modelin tahmin artiklarinin hatalarinin uzerine kurularak olusturulur.
GBM diferansiyellenebilen herhangi bir kayip fonksiyonunu optimize edebilen Gradient descent algoritmasini kullanmaktadir.
GB bir cok temel ogrenici tipi kullanabilir.
Cost fonksiyonlari ve link fonksiyonlari modifiye edilebilirdir.
Boosting+Gradient Descent

# XGBoost
GBM'in hiz ve tahmin performansini arttirma icin optimize edilmis.