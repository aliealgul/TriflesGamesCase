# TriflesGamesCase
Trifles Games 3D Artist Case Study

Projeye ve iş akışına ait belirtmek istediğim detaylar:

 - Modellerin genelinde tek renk material kullandığımdan dolayı yalnızca gereken yerlerde UV açtım.
 
 - Dosyalama sistemi genel hatlarıyla şu şekilde
	- Model, texture, material vb. öğeler klasörledim,
	- Benzer nitelikli objeler (vehicles, environment vb.) klasörledim,
	- Aynı objelerin farklı renklerini üretmek için Unity'nin özelliklerinden olan "prefab variant" sistemini kullandım,
	- Unity sahne içinde de benzer hiyerarşiyi kullandım.
 
 - Arkadaki kamyonun içindeki boya kutularını statik modelledim. Konsepte yakın bir sonuç elde etmenin bu şekilde daha hızlı 
 olacağını düşündüğüm için böyle yaptım.
 
 - Araçların meshlerini parçalar halinde hazırladım. Böylelikle araç çeşitlendirme ve fiziksel hareketlerde tekerlek hareketleri
  gibi özellikler eklemeye uygun olacağını düşündüm,

 - Proje genelinde mümkün olduğunca texture kullanmamaya çalıştım. Bunun sebebi renk paletini gerekli görülürse değiştirilebilir
 yapmak istememdi,
 
 - Textlerde ve arayüzde Unity'nin "TextMeshPro" eklentisini kullandım. Bunun yine değiştirilebilirlik açısından yarar sağlayacağını
 düşündüm,
 
 - Liquid Tank objelerinde, tankın içindeki sıvılara BlendShape ekledim. Sıvının doluluk yüzdesi developer tarafından kolaylıka
 ayarlanabilir.

 - Software Versions
	- Unity 2020.3.21f1
	- Blender 3.1.2
	- Adobe Photoshop 2020