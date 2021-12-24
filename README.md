# Javascript ile Birlikte Dinamik Olarak Değişen Bir Site Oluşturmak.

* Javascript içerisinde sitenin içeriğini oluşturan key,value ilişkilerinden meydana gelen birden fazla nesne bulunmaktadır. Öncelikle o nesnelerdeki kategori anahtarı js'in map fonksiyonu kullanılarak çekilmiş, ardından bu kategorilerden tekrar edenler elimine edilerek yeni bir diziye aktarılmıştır ve bu yeni dizi sayesinde dinamik butonlar oluşturulmuştur. Bu butonlar sayfalar arasında geçişleri sağlayan Korea, Japan gibi butonlardır.
* Daha sonra her bir sayfa için ayrı bir fonksiyon tanımlanmış ve her bir fonksiyonun içerisinde sayfanın içerisinde görünecek içeriğe göre filtreleme işlemi yapılmıştır. Bu filtreleme işlemi için js'in filter işlevi kullanılmıştır.
* Bunun dışında sayfa yüklenirken bütün içeriklerin ekranda görüntülenmesi sağlanmıştır.

![Menu](menu.gif)
