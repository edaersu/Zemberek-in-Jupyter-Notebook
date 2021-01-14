## Zemberek kütüphanesini Jupyter Notebook'da Kullanma

Zemberek, açık kaynak kodlu Türkçe Doğal dil işleme kütüphanesidir.Tamamen Java ile geliştirilen kütüphane, yazım denetimi, hatalı kelimeler için öneri, heceleme, deascifier, hatalı kodlama temizleme gibi işlevlere sahiptir.<br>
Python kodu içerisinde bu kütüphaneyi kullanabilmemiz için JVM(Java sanal makinesi) ve bazı jar dosyalarının pathlerini kodda belirtmemiz gerekiyor.<br>

Adımlar:<br>
1-Java kurulumu<br>
2-Kullanılacak jar dosya/dosyalarını indirme<br>
2-Path değişkenlerini belirleme<br>
Runn :)<br>

1- Bilgisayarınızda Java kurulu değil ise  [buradan](https://www.java.com/tr/) Java yazılımını indirip kurmanız gerekiyor.<br>

2-Daha sonra [buradan](https://drive.google.com/drive/folders/0B9TrB39LQKZWX1RSang3M1VkYjQ) güncel zemberek jar dosyasını indirebilirsiniz. Eğer 1'den fazla jar dosyasını aynı notebook üzerinde kullanmak istiyorsanız hepsini indirip tek tek pathlerini tanımlayıp bunu bir listede tutabilirsiniz. (zemberek-örnek.ipynb'da olduğu gibi)<br>
Örnek olarak bu repodaki "zemberek-tum-2.0.jar" dosyasını kullanabilirsiniz.

3- Benim bilgisayarımda;<br>
jvm.dll >> "C:\Program Files\Java\jdk-11.0.8\\bin\server\jvm.dll"<br>
zemberek-tum-2.0.jar >> "C:\Users\Eda\Desktop\zemberek\zemberek-tum-2.0.jar" <br>
şeklinde adreslerde bulunuyor. Sizde indirme işlemlerinden sonra bu pathleri belirleyip zemberek-örnek.ipynb içerisinde değiştirmeniz gerekiyor.<br>

**Son olarak Notebook'da kullanılan bir diğer jar dosyası "zemberek-full.jar" dosyasını [buradan](https://drive.google.com/file/d/1RRuFK43JqcHcthB3fV2IEpPftWoeoHAu/view?usp=sharing) indirerek path'i jar2 değişkenine atarsanız notebook sorunsuz çalışacaktır.(Dosya boyutu dolayısıyla repoya koyamadım)

"zemberek-full.jar" içerisindeki class ve methodlara ise [bu repodan](https://github.com/ahmetaa/zemberek-nlp) erişebilirsiniz
