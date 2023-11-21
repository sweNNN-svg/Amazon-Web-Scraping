Amazon Webscraping Projesi
Bu projeler, Amazon Türkiye sitesindeki mekanik klavye ürünleri ile ilgili verileri çekmek ve işlemek amacıyla Python ve BeautifulSoup kütüphanesi kullanılarak geliştirilmiştir. Aşağıda projelerin detaylı açıklamalarını bulabilirsiniz.

tr_amazon_web_scraping-tutorial.ipynb
Bu Jupyter Notebook dosyası, Amazon Türkiye sitesinden mekanik klavye ürünleriyle ilgili veri çekme işlemini adım adım gösterir. Aşağıda kodun temel adımları yer almaktadır:

Belirli bir Amazon Türkiye URL'sinden sayfa içeriğini çekme.
BeautifulSoup kütüphanesi kullanarak sayfa içeriğini parse etme.
Ürünlerin bulunduğu linkleri çıkarma.
İlk ürünün linkini seçme.
Seçilen ürünün detaylarını çekme (başlık, fiyat, değerlendirme).


tr_amazon_web_scraping.ipynb
Bu Jupyter Notebook dosyası, tr_amazon_web_scraping-tutorial dosyasında gösterilen adımları içeren bir Python kodunu içerir. Ayrıca, çeşitli fonksiyonları içerir:

get_product_title: Ürün başlığını çekme.
get_product_price: Ürün fiyatını çekme.
get_product_rating: Ürün değerlendirmesini çekme.
Bu fonksiyonlar, belirli bir ürün sayfasındaki başlık, fiyat ve değerlendirmeyi çekmek için kullanılır. Ana kod, belirli bir Amazon Türkiye URL'sinden ürünlerin linklerini çeker ve bu linkler üzerinden ürün detaylarını çekip bir veri çerçevesine kaydeder. Sonuçlar, "tr_amazon_data.csv" adlı bir CSV dosyasına kaydedilir.

Önemli Not:
Projeyi çalıştırmadan önce, gerekli kütüphanelerin yüklü olduğundan emin olun ve Amazon'un web sitesine yönelik veri çekme işlemlerinin hukuki ve etik kurallarını dikkate alın. Veri çekme işlemleri, sitenin kullanım şartlarına uygun olarak gerçekleştirilmelidir.





