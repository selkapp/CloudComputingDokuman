# CloudComputingDokuman


CLOUD COMPUTİNG (BULUT BİLİŞİM)                           
Bilgisayar Mühendisliği Bölümü
       Kocaeli Üniversitesi

ÖZET
Cloud Computing, uygulama ve servislerin internetteki sunucular üzerinde bulundurulması, internete bağlı herhangi bir cihaz ile uygulama ve servislerin çalıştırılmasıdır. Bulut Bilişim ile bilgisayarınızda bulunan ofis, resim düzenleme ve arşivleme, ajanda, yabancı dile çeviri programları ve kişisel dosyalarınız, internetteki bir sunucuya taşınıyor ve internete bağlı olduğunuz her yerden bu programlara ulaşarak çalışmalarınızı yapabiliyorsunuz.
Bulut Bilişim, düşük yönetim çabası veya servis sağlayıcı etkileşimi ile, hızlı alınıp salıverilen ayarlanabilir bilişim kaynaklarının paylaşılır havuzuna , istendiğinde ve uygun bir şekilde ağ erişimi sağlayabilen  bir modeldir .
 
1.GİRİŞ 
Bulut bilişim işlem gücünün, veri tabanı depolama alanının, uygulamaların ve diğer BT kaynaklarının bir bulut hizmetleri platformu tarafından internet üzerinden  istek üzerine ve kullandıkça ödeme modeliyle sunulmasıdır.  Bu modelin iki önemli avantajı kullanım kolaylığı ve maliyet etkinliği,  güvenlik gibi konularda sorular kalsa da  satıcı kilidi, bu modelin sunduğu avantajlardandır. Bu çalışma, bazı bulut bilişimin temelleri, aşağıdaki gibi yönleriyle tanıtmak için bize kaynak sağlayacaktır. [2],[3]
➢	Modelin gerçekleri ve Riskleri

➢	Modeldeki Bileşenler

➢	Modelin özellikleri ve kullanımı


2. BULUT BİLİŞİM ÖZELLİKLERİ 
•	Self servis
•	Çevrimiçi her zaman erişilebilir .
•	Her şey tarayıcıyla sağlanıyor .
•	Ölçeklendirilebilir ,kuvvetli ve güvenlidir.
•	Abone modeli(Özel veya paylaşımlı )
•	Zamanda tasarruf sağlar.
•	Maliyette ucuzluk sağlar.(Kullandığın kadar ödeme )
•	Kapasite de artım  sağlar.

3. BULUT BİLİŞİM ALTYAPISI
      

Bu yapı ile;
➢	Yedekli, hızlı ve kesintisiz bir altyapıya, 
➢	 Düzgün bir veri merkezi ortamında çalışan BT altyapısına, 
➢	 Bu datacenter(veri merkezi) içinde konumlandırılmış; 
•	Mail, Sunucu, Hat Güvenlik Ürünlerine (FW, Router, IPS vb.)
•	Arşivleme ve Yedekleme Çözümlerine, 
•	Elektrik, UPS, Soğutma Sistemlerine, 
•	Sunucu ve uygulamalara sahip olunabilmekte
•	Network altyapısına
Klasik BT altyapısın da farklı olarak aşağıdaki gibi bir maliyet oranlaması çıkmaktadır.



4. BULUT BİLİŞİM MİMARİSİ 
Bir bulut bilişim sistemi genel olarak ön taraf ve arka taraf olmak üzere iki kategoride değerlendirilir. Bu iki kısım birbirlerine bir ağ ve genellikle internet ile bağlıdır. Ön taraf bilgisayar kullanıcısı veya müşteri tarafıdır. Arka taraf ise sistemin bulut kısmıdır.

➢	Ön taraf, istemcinin bilgisayarını (veya bilgisayar ağını) ve bulut bilişim sistemine erişim için gerekli olan uygulamayı içerir. Bütün bilişim sistemleri aynı kullanıcı ara yüzüne sahip değildir. Web tabanlı e-posta  programları  gibi  hizmetler  herhangi  bir  web  tarayıcısı kullanarak  çalışabilir.  Diğer sistemler istemcilere ağ erişimi sağlayan birbirinden farklı uygulamalar sağlarlar.
➢	Sistemin arka tarafında bilişim hizmetlerinin bulutunu oluşturan çeşitli bilgisayarlar, sunucular, veri depolama sistemleri vardır. Teoride, bir bulut bilişim sistemi pratik olarak veri işlemeden video oyunlarına kadar bütün bilgisayar programlarını içerebilir. Genellikle herbir uygulamanın kendine ait bir sunucusu vardır.


Bir merkez sunucusu sistemi yönetir, trafiği ve istemci taleplerini her şeyin yolunda gidip gitmediğinden emin olmak için sistemi izler. Protokoller denilen bir takım kuralları izler ve middleware denilen (ara  bir  yazılım) özel  bir  yazılım  kullanır. Ara yazılım ağ bağlantılı bilgisayarların birbiriyle iletişim kurmasını sağlar.  Çoğu durumda sunucular tam kapasite çalışmazlar. Bu kullanılmayan işleme gücünün boşa gitmesi anlamına gelir. Fiziksel  bir sunucuyu aslında her biri kendi bağımsız işletim sistemini çalıştıran çoklu sunucularmış gibi   kullanmak   mümkündür. Bu   tekniğe   sanallaştırma   denilmektedir.   Sunucu sanallaştırması birbirinden ayrı bulunan sunuculardan en iyi şekilde faydalanılmasıyla daha az fiziksel makineye ihtiyaç duyulmasına sebep olur.

Eğer bir bulut bilişim şirketi birçok istemciye sahip ise, depolama alanı için yüksek bir talep olması muhtemeldir. Bazı şirketler yüzlerce dijital depolama cihazı gereksinimi duyar. Bulut bilişim  sistemleri  bütün  istemcilerinin  bilgilerini  koruyabilmek  için  asgari  çiftli  depolama cihazları bulundurmalıdır. Bunun sebebi bu cihazlar aynı bilgisayarlar gibi kimi durumlarda arızalanmaktadır.  Bir  bulut  bilişim  sistemi  bütün  istemcilerinin  bilgilerinin  kopyasını oluşturmalı  ve  diğer  depolama  cihazları  üzerinde  depolamalıdır.  Bu  kopyalar merkez sunucunun yedek makinelere erişmesine ve verileri geri getirmesine izin verir aksi takdirde verilerde kayıplar yaşanabilir. 



•	Tüketici : Servis sağlayıcının sunduğu hizmetleri (yazılım, platform ya da altyapı servisleri) tüketen kurum ya da bireylerdir. Genellikle abone oldukları servisleri “kullandıkça öde” modeline göre kullanırlar. Abonelik, sağlanan web arabirimi ya da programlama ara yüzleri(API)  ile program içerisinde gerçekleştirilir. Tüketici, servis sağlayıcı ile hizmet seviyesi anlaşması (SLA) ya da kontrat esasına göre çalışıyor olabilir. Tüketici gerçekleştireceği fonksiyona ya da role bağlı olarak farklı kullanıcı arabirimi ya da programlama ara yüzü kullanıyor olabilir. 

Örneğin, kullandığı sanal makinayı çalıştırmak, durdurmak, silmek gibi yönetsel işler için web arabirimini kullanabileceği gibi uygulama içerisinden API  kullanıyor  olabilir.  Servis sağlayıcı tüketiciye servisin kullanımı hakkında detaylı analitik bilgi sunabilmelidir. Servis sağlayıcı kullanıcıya servisi kullanabilmesi ve kullanırken oluşan problemleri giderebilmesi için gerekli yardımı sağlar. Tüketici; abonelik, yönetim, yardım, servisin tüketimi işlemlerini erişim katmanı üzerinden gerçekleştirir. Erşim katmanı, web ara yüzü ve API’lerdir.

•	Servis Sağlayıcı : Servisi planlayıp kurar ve tüketiciye ulaştırır. Sunduğu servisler temel olarak, altyapı (IaaS), platform (PaaS), yazılım (SaaS) servisleridir. Servis geliştiricilerin geliştirdiği uygulama ve servisler bunların üzerine kuruludur. Uygulama katmanı ile gösterilen budur. 

Çizimin en altında görülen donanım katmanı, servislerin üzerinde koştuğu fiziksel donanımı göstermektedir. Sunucular, veri saklama cihazları, iletişim ekipmanları bunlardan bazılarıdır. 
Donanımın hemen üstünde çekirdek  yazılım  ile  ifade  edilen  kısım,  işletim  sistemi  ya  da  sanal  makina  yönetim katmanıdır.  Sanallaştırma  bu  aşamada  başlamaktadır.  
Çekirdek  yazılımın  üstünde  bilgi işleme,  veri  saklama,  iletişim  ağları  gibi  sanallaştırılmış  kaynaklar  bulunmaktadır. Sanallaştırma Bulut Servislerinin, en belirgin özelliğidir.
Fiziksel  bir sunucuyu aslında her biri kendi bağımsız işletim sistemini çalıştıran çoklu sunucularmış gibi   kullanmak   mümkündür.   Bu   tekniğe   sanallaştırma   denilmektedir. Sunucu sanallaştırması birbirinden ayrı bulunan sunuculardan en iyi şekilde faydalanılmasıyla daha az fiziksel makineye ihtiyaç duyulmasına sebep olur.

•	Servis Geliştirici : Servis sağlayıcının sunmuş olduğu temel servisleri alıp yeni uygulama ya da servisler oluşturur. Bunun için servis oluşturma, yayınlama ve izleme fonksiyonlarının servis sağlayıcı tarafından sağlanmasına gereksinim duyar. Oluşturduğu servis ile ilgili analitik bilgi geliştirici için önemlidir ve servis sağlayıcı tarafından sağlanmalıdır. Tamamen yeni bir servis  geliştirebileceği  gibi, var olan servisi kendi markasını oluşturarak yeni bir alana pazarlıyor da olabilir.

5. BULUT BİLİŞİM TÜRLERİ 
4 ayrı çeşidi ile karşımıza çıkan bu teknoloji  farklı alanlarda ,farklı biçimlerde kullanılmaya olanak sağlıyor.[5][6][10][12]       
 

5.1 Public Cloud (Genel Bulut):

➢	 Genel Bulut (Public Cloud), internet erişimine sahip tüm şahıs veya kuruluşlar için veri aktarımı yapan platformlar (web ve e-ticaret siteleri, vb.) için kullanılan bilişim hizmetinin adıdır. 
➢	Genel bulutta tüm donanım, yazılım ve diğer destekleyici altyapı bulut sağlayıcısına aittir ve bu sağlayıcı tarafından yönetilir.
➢	Web tabanlı e-posta, çevrimiçi ofis uygulamaları, depolama, test ve geliştirme ortamları sağlamak için sıklıkla genel bulut dağıtımları kullanılır.
➢	Genelde küçük ve orta ölçekli firmalarda kullanılır.

       Genel Bulut’un kullanıcılarına sağladığı avantajlar;

•	Düşük maliyet
•	Bakım gerekmez
•	Sınırsıza yakın ölçeklenebilirlik
•	Yüksek güvenilirlik

                                                                                    

5.2 Private Cloud (Özel Bulut):

➢	Private Cloud daha büyük şirketler ve bilgileri daha önemli olan şirketlerin tercih ettiği bir bulut teknolojisi tipidir.
 


➢	Özel bulut, özel olarak tek bir işletme veya kuruluş tarafından kullanılan bulut bilgi işlem kaynaklarından oluşur. Özel bulut, kuruluşunuzun tesis içi veri merkezinde fiziksel olarak bulunabileceği gibi üçüncü taraf bir hizmet sağlayıcı tarafından da barındırılabilir.

➢	Özel bulutlar,  şirket güvenlik duvarları ve dahili barındırma aracılığıyla üst düzeyde güvenlik ve gizlilik sunarak üçüncü taraf sağlayıcıların işlemlere ve gizli verilere erişimini önler.

➢	Örnek olarak devlet kuruluşları bilgi işlem ihtiyaçlarını ortak kurulan bir bulut kullanarak sağlayabilirler. Yada uluslararası bir şirket tüm dünya ülkelerinde olan şubelerinin bilgi işlem ihtiyaçlarını tek bir bulut üzerinden sürdürebilmektedir.

        Özel Bulut’un kullanıcılarına sağladığı avantajlar;

•	Daha fazla esneklik
•	Yüksek Güvenlik
•	Yüksek ölçeklenebilirlik

5.3 Hybrid Cloud (Karma Bulut):

➢	Hybrid Cloud, Public ve Private Cloud’un birleşiminden ortaya çıkan yapılardır. 
                                
                      

➢	Şirket içi altyapıyı, diğer bir deyişle özel bulutları genel bulutlarla bir araya getiren karma bulutlar, kuruluşların bu iki bulut türünün de sağladığı avantajları bir arada elde etmesini sağlar. Karma bulutta, verilerle uygulamalar daha yüksek esneklik ve daha fazla dağıtım seçeneği sağlayacak şekilde özel ve genel bulutlar arasında taşınabilir. 

➢	Genel bir örnekleme yapmamız gerekirse, bir kuruluş veya sistemin tüm Cloud sistemlerini tek bir noktada toplayarak, bilgi ve yazılımların daha senkron bir şekilde yönetilmesini ve daha esnek bir şekilde erişime açık olmasını sağlamaktadır.

Karma bulutun kullanıcıya sağladığı avantajları;
•	Denetim
•	Esneklik
•	Maliyet etkinliği
•	Kolaylık

5.4.Community Cloud (Topluluk Bulut):

➢	Çok fazla kullanılmayan Community Cloud, bulutun üzerinde alınan herhangi bir hizmetin birkaç şirket ile ortak kullanılması durumuna denmektedir. Firmalar topluluk bulut teknolojisini çok kullanmazlar ancak birden çok firması olan kişiler için ideal bulutlardan biridir. 

                   

6. BULUT BİLİŞİM KULLANIM SENARYOLARI 
•	Bireysel Kullanım
•	Kurumsal Kullanım
•	Tekil Sağlayıcılı Bulut Servisi 
•	Çoğul Sağlayıcılı Bulut Servisi
•	Servis Geliştirici 

6.1 BİREYSEL  KULLANIM

➢	Bu senaryoya göre tüketici bireysel kullanıcıdır ve Bulut servislerini kullanır. Tüketici arka planda servisin nasıl oluşturulduğu ya da nasıl çalıştığı ile ilgilenmez .Kullandıkça öde en yaygın kullanılan iş modelidir. Bu tür servislere örnek verecek olursak ‘ Amazon S3’ servisi iyi bir örnektir.

       6.2 KURUMSAL  KULLANIM

➢	Bu senaryo içerisinde birden çok alt senaryo barındırmaktadır. Bu senaryoların ilkinde, İşletme son kullanıcılara kullandırmak üzere (çalışanlar, iş ortakları, müşteriler, vb.) Bulut servislerinden faydalanır. Elektronik posta ya da veri paylaşımı servisleri örnek olarak verilebilir .
➢	İkinci senaryoda, BT fonksiyonlarının bazılarının Bulut servislerine aktarıldığını görürüz. Veri saklama, yedekleme ve veri tabanı servisleri ilk anda verebilen örneklerdir. Kurum BT servislerini birbirinden bağımsız hale getirebildiği ölçüde Bulut servislerinden yararlanma oranı artacaktır. Servis Odaklı Mimarinin kurum içerisindeki adaptasyonu/uygulanması belirleyicidir.
➢	Üçüncü senaryoda, kurum BT altyapısını tamamen Bulut üzerine aktarırlar. Bir ve ikinci senaryolar dışında kalan her şey Bulut üzerindeki sanal bilişim kaynaklarına aktarılır. Bir tür sanal veri merkezi oluşturmak söz konusudur 
➢	Dördüncü senaryoda ise kurum verimliliğini artırmak maliyetlerini düşürmek için servis sağlayıcı mimarisini kendi veri merkezinde hayata geçirir. Bir ve ikinci senaryolar yine bu senaryo ile kombine edilebilir. Kurumlarının Bulut servislerinden hangi senaryoları kullanarak ve hangi oranda yararlanabilecekleri, kurum stratejisine ve kurum BT altyapısının esnekliğine bağlıdır. Bunun için bir tür Servis Odaklı Mimari olgunluk modeli oluşturulabilir.[11]

6.3 TEKİL SAĞLAYICI BULUT SERVİSİ 

➢	Bu senaryoda servis sağlayıcı tüm BT altyapısını, yani altyapı, uygulama platformu  ve yazılım servislerini tek elden sunar. Google Apps ve Microsoft Office Live örnek olarak alınabilir.

6.4 ÇOĞUL SAĞLAYICI BULUT SERVİSİ 

➢	Bulut Bilişim yaklaşımının ne kadar esnek olduğunu göstermesi açısından son derece ilginç olan bu senaryoda; servis aldığımız servis sağlayıcı servisini bir ya da daha çok servis sağlayıcının sunduğu servisler üzerine kurar. Örneğin; fotoğraf paylaşım servisi olan SmugMug veri saklama hizmetini Amazon S3 den almaktadır. Ama bu servisi kullanan tüketici yalnızca SmugMug ile muhattap olur, gerisinden haberi olmaz.

6.5  SERVİS GELİŞTİRİCİ 

➢	Bu senaryoda servis geliştirici (bu kurum ya da birey olabilir) servis sağlayıcı tarafından sağlanan  geliştirme ortamı ile belli servis sağlayıcı çalıştırma ortamı (runtime) için uygulamasını ya da servisi geliştirir. Yalnız bu uygulama/servis arka planda birden çok servis sağlayıcının sunduğu  servis ya da altyapıyı kullanabilir. 
Örneğin; Google Apps Engine için geliştirme yapan bir geliştiriciyi düşünelim. Bu geliştiricinin büyük miktarda saklama alanına ve ilişkisel veri tabanına ihtiyacı olduğunu varsayalım. Google Apps Engine bu gereksinimleri karşılayamaz ama Amazon S3 ve EC2 karşılayabilir. Sonuçta Google Apps Engine üzerinde çalışan uygulama/servis aynı zamanda Amazon servislerini de kullanıyor olur. Daha farklı senaryoları da düşünmek mümkündür, örneğin Bulut servisleri arasında uygulama ve verinin taşınması.[7][8]

7. BULUT BİLİŞİM KULLANIM ALANLARI 
Dosya Depolama ve Yedekleme

➢	Bulut, dosyalarınızı depolama ve onlara herhangi bir web-etkin arayüzden erişme, depolama ve geri alma olanağı sunar. 
➢	Herhangi bir zamanda ve yerde ortamınız için yüksek kullanılabilirlik, hız, ölçeklenebilirlik ve güvenlik sağlar.
➢	Bulut servis sağlayıcınız, verileri güvenceye almak ve yasal ve uyumluluk gereksinimlerini karşılamaktan sorumludur. Bu, altyapı ve bakım oluşturmak için sizi sermaye harcamalarından kurtarır


Big Data Analizi

➢	Bulut bilişimden yararlanarak sunulan özelliklerden biri de, iş değerlerinin çıkarılmasının yararını sağlamak için, big dataların madenciliğine imkan sağlamasıdır.
➢	Veri destekli karar vermede yardımcı olmak için bir takım organizasyonel verilere erişimlerine imkan sağlar.
➢	Hadoop, Cassandra, HPCC da buluta dayanan açık kaynak kodlu büyük veri araçlarına örnek verilebilir.[15]

Chatbots

➢	Genişletilen bilgi işlem gücü ve bulut kapasitesi, kullanıcı tercihleri hakkında bilgi depolamamızı sağlar. Bu, kullanıcıların davranışlarına ve tercihlerine göre özelleştirilmiş çözümler, mesajlar ve ürünler sağlamak için kullanılabilir.
➢	Siri, Alexa ve Google Asistan - hepsi bulut tabanlı doğal dil akıllı botlardır. Bu sohbet kutuları, kişiselleştirilmiş bağlamla ilgili müşteri deneyimleri sağlamak için bulutun bilgi işlem yeteneklerinden yararlanır.

Test ve Geliştirme

➢	Bulut, giderleri düşürmek ve uygulamalarınızı piyasada daha hızlı başlatmak için bir ortam sağlar.
➢	Fiziksel ortamları kurmak yerine geliştiriciler, testi ve geliştirme ortamlarını kurmak ve kaldırmak için buluta başvurabilirler. Bu teknik ekibi, bütçeleri güvenceye almaktan ve kritik proje zamanı ile kaynakları harcamaktan kurtarır. 
➢	Bu dev-test ortamları da gereksinimlere göre ölçeklendirilebilir veya azaltılabilir. LoadStorm ve BlazeMeter popüler test araçlarıdır.

İletişim

➢	Bulut kullanıcıların, e-postalar ve takvimler gibi iletişim araçlarına, ağ tabanlı erişim ile yararlanmalarını sağlar. Skype ve WhatsApp gibi mesajlaşma ve çağrı uygulamalarının çoğu da bulut altyapısına dayanmaktadır. 
➢	Tüm mesajlarınız ve bilgileriniz, kişisel cihazlarınız yerine servis sağlayıcınızın donanımında saklanır. Bu, bilgilerinizin internet üzerinden her yerden erişebilmesini sağlar.

Verimlilik

➢	Microsoft Office 365 ve Google Dokümanlar gibi ofis araçları, en verimli araçlarınızı internet üzerinden kullanmanıza olanak tanıyan bulut bilişimi kullanırlar. Belgeleriniz, sunumlarınız ve e-tablolarınız üzerinde istediğiniz zaman çalışabilirsiniz.
➢	Verileriniz bulutta depolandığında, cihazınızın çalınması, kaybolması veya zarar görmesi durumunda veri kaybına uğramazsınız. Cloud ayrıca belgelerin paylaşılmasına da yardımcı olur ve aynı kişilerin aynı belgede aynı anda çalışmasını sağlar.

Sosyal Ağ

➢	Sosyal Medya, bulut bilişimin en popüler ve genellikle gözden kaçan uygulamasıdır. Facebook, LinkedIn, MySpace, Twitter ve diğer birçok sosyal ağ sitesi bulut bilişimini kullanıyor. Sosyal ağ siteleri, zaten bildiğiniz veya bilmek istediğiniz kişileri bulmak için tasarlanmıştır. İnsanları bulmak için çok fazla kişisel bilgi paylaşıyoruz. Tabii ki, eğer sosyal medyada bilgi paylaşıyorsanız, onu sadece arkadaşlarla değil, aynı zamanda platformun yapımcılarıyla da paylaşıyorsunuz. 
➢	Bu, platformun verileri gerçek zamanlı olarak yönetmek ve depolamak için güçlü bir barındırma çözümü gerektireceği anlamına gelir.Bulut bilişim bu gibi durumlar için önemli bir çözüm önerisidir.

8. BULUT BİLİŞİM HİZMET MODELLERİ 
Bulut Bilişim (Cloud Computing), kullanıcıların yerel konumlarında yazılım, veri erişimi veya servis altyapısı gerekmeksizin alınacak ihtiyacın hizmet olarak sağlanmasıdır. Bulut Bilişim hizmeti Infrastructure as a Service (IaaS), Platform as a Service (PaaS), Software as a Service (SaaS) olarak 3 şekilde sunulmaktadır. 

•	Hizmet Olarak Yazılım (SaaS- Software as a Services)

•	Hizmet Olarak Platform (PaaS)

•	Hizmet Olarak Altyapı (IaaS)



8.1  Hizmet Olarak Yazılım (SaaS- Software as a Service)


➢	Kullanıcıların ihtiyaç duyduğu CRM, ERP, finans ve muhasebe yazılımları gibi programları bulut üzerinde sağlar.
➢	En büyük bulut pazarını temsil etmekte ve hala hızla büyümektedir. Çoğu SaaS uygulaması herhangi bir indirme veya kurulum gerektirmeden doğrudan bir web tarayıcısından çalıştırılabilir, ancak bazıları eklentileri gerektirebilir. 
➢	Web dağıtım modeli sayesinde SaaS, uygulamaları tek tek bilgisayarlara kurma ve çalıştırma gereksinimini ortadan kaldırmaktadır. Farklı lokasyonlarda faaliyet gösteren firmalar için SaaS ekstra yazılım maliyeti oluşturmayarak ciddi ekonomik avantaj sağlar.  
➢	SaaS ile işletmelerin bakım ve desteğini kolaylaştırır.

SaaS’ın Faydaları;

Başlangıç maaliyetlerinin ortadan kaldırılması: SaaS genellikle bir abonelik temelinde sağlanır, çünkü geleneksel olarak yazılım uygulamayla ilişkilendirilen ilk maliyetleri ortadan kaldırır. SaaS ilk maliyet bariyerinin aşılmasına ve sofistike sistemlere daha kolay ve daha uygun fiyatlı erişime imkan verir.

Kullanma bırakıldığında ödemeninde durması : SaaS sisteminin bir diğer yararı, bir abonelik artık yazılımı gerektirmediğinde sözleşmenizi feshetme imkanınız vardır.

Güvenli veri : SaaS ile buluta bağlı yazılım sistemlerini kullanarak dosyaları yerel bir aygıta depolamadaki güvenlik açığını ortadan kaldırmış olursunuz. Ayrıca elinizin altında her zaman dijital bir yedekleme bulunur.

Esneklik : SaaS'ın başlıca avantajlarından biri sunduğu esnekliktir. İhtiyacınız olan uygulamalara basit bir internet bağlantısı kullandığınız her yere erişebilirsiniz.

8.2 Hizmet Olarak Platform(PaaS- Platform As A Service) 
  	                          	  

➢	İngilizcesi Platform as a Service (PaaS) olan Platform hizmeti, uygulama geliştiricilere donanım ve yazılım katmanları sunarak projelerini geliştirme imkanı sağlar. 
➢	PaaS, uygulamaların hızlı, basit ve uygun maliyetli geliştirilmesini, test edilmesini ve entegrasyonunu sağlar. Bu teknoloji ile kurumsal işlemler veya bir üçüncü taraf sağlayıcı işletim sistemlerini, sanallaştırmayı, sunucuları, depolamayı, ağ ve PaaS yazılımını kendisi yönetebilirler.
➢	PaaS, geliştiricilerin web veya mobil uygulamalarını, geliştirme için gereken sunucu, depolama, ağ ve veritabanlarının temel altyapısını kurma ve yönetme gibi zorluklar olmadan hızla oluşturması amacıyla tasarlanmıştır.


PaaS’ın Faydaları;

Maliyetin düşmesi: Geçmişte, geliştirilen yazılım, gerekli donanım, beceri ve deneyim sonucunda pahalıydı. Bunun yerine PaaS, kullanıcıların abonelik ücreti karşılığında verdiği gerekli altyapıyı etkili bir şekilde kiralamasına izin verir.

Beceri engelinin ortadan kaldırılması: PaaS sistemleri genellikle kullanımı kolaydır, yani işletmeler, uygulamalarını geliştirmek için uzman çalıştırma ihtiyacı hissetmezler. Daha ziyade, bir uygulama yalnızca bir web tarayıcısı aracılığıyla şirket içinde geliştirilebilir.

Artan işbirliği: Büyük işletmelerde birden fazla taraf aynı uygulama geliştirme projesinde çalışıyor olabilir. Bulut bağlantısıyla, farklı konumlardaki çok sayıda geliştirici, aynı proje üzerinde işbirliği yapabilir.

8.3 Hizmet Olarak Altyapı(IaaS- Infrastructure As A Service)

➢	Uzak veri merkezi altyapılarını yönetmek için bir self servis modelidir. IaaS ile sanal sunucu oluşturulup kullanıcılara bulut sunucu hizmeti sunulmaktadır.
➢	IaaS, otomatik olarak tedarik edilen, ölçülebilen ve isteğe bağlı olarak kullanılabilir bulut depolama ve ağ yeteneği ile tamamlanmış, son derece otomatikleştirilmiş ve ölçeklenebilir hesaplama kaynakları içermektedir. 
➢	IaaS, bir bulut sağlayıcısından kullanıldıkça ödeme yapılması esasına dayanan bir sistem olup sunucular, sanal makineler (depolama, ağ, işletim sistemleri) kiralanmasını sağlar. 

IaaS’ın Faydaları;

Ölçeklenebilirlik: : IaaS'in başlıca avantajlarından birisi sunduğu ölçeklenebilirliktir. Bir abonelik hizmeti aracılığıyla, ihtiyaç duyduğunuz bilgi teknolojileri sistemine erişebilirsiniz. Sanallaştırması nedeniyle, sistemlerinizin hızlandırılması hızlı ve verimli bir şekilde yapılabilir, bu da arıza süresini en aza indirir.

En düşük donanım bakımı: IaaS sisteminizin arkasındaki donanım dışardan yönetilir ve işletmenizin bu bakım türüne harcadığı zaman ve parayı en aza indirir.

Esneklik: Birçok IaaS sistemi uzaktan erişilebilir, ancak bu sistemden sisteme değişiklik gösterecektir.

Kesinti süresinin azaltılması: Donanımınız bozulursa, genelde personelinizin ve işinizin verimliliğini etkileyen tamir beklemeniz gerekir. Bir IaaS sistemi çok sayıdaki sunucu ve veri merkezini kullanır. Bu durum bir alan başarısız olursa, boşluğu doldurmak için diğer donanım kaynaklarının kullanılabilirliğini sağlar.

İsteğe bağlı erişim: Bir IaaS sistemi isteğe bağlı olarak erişilebilirdir. Yalnızca kullandığınız kaynaklar için ödeme yapıldığından maliyetleri düşürürsünüz. 

SaaS, PaaS, IaaS Arasındaki Farklar Nelerdir?
 



9. BULUT BİLİŞİM AVANTAJLARI VE DEZAVANTAJLARI
AVANTAJLARI

•	Düşük Donanım Maliyeti :Uygulama bulutta çalıştırılıyor. Dolayısıyla minimum kaynak kullanımıyla      günümüzün en güçlü bilgisayarlarının performanslarına erişebiliyorsunuz. 

•	Düşük Yazılım Maliyeti: Sadece kullanıcıların ihtiyaç duyduğu uygulamalara erişim sağlanır. Ayrıca yazılımları satın almak yerine kiralayabiliriz.

•	Gelişmiş Performans:  Çok daha az sistem kaynağı tükettiği için sisteminizde herhangi bir performans kaybı yaşamazsınız.

•	Anında Güncelleme: Uygulamanın yeni sürümü çıktığında veya bazı açıkları kapatmak için güncelleme yayınlandığı anda siz de en güncel sürümü edinmiş olursunuz.

•	Artırılabilir Depolama Kapasitesi 

•	İşletim Sistemleri Arasında Geliştirilmiş Uyum: Veriler sunucuda bulunduğu için herhangi bir işletim sistemiyle bu dosyalara sorunsuz bir şekilde ulaşabilirsiniz. Platform bağımlılığı yoktur.

•	Gizlilik ve Güvenlik: Bilgileri yanınızda taşımanıza gerek kalmaz. Dizüstü sisteminizin düşüp bozulması, kaybolması ya da çalınması, bilgilerinizin kaybı ile sonuçlanmaz önemli her şey buluttan geri yüklenebilir. 

DEZAVANTAJLARI

•	Sabit İnternet Bağlantısı Gerektirmesi 

•	Düşük Hızlarda Düzgün Çalışmaması 

•	Sistem Güncellemeleri:Bulut üzerinde bir yazılım çalıştırıyorsanız, bulut altyapısı güncellendiğinde, kullandığınız yazılım bu güncelleme ile sorun yaratabilir. 

•	Uygulamanın Yavaş Çalışması : Eğer web tabanlı uygulama ve servisi çalıştıran sunucu aşırı yoğunsa kullandığınız  uygulama normalden daha yavaş çalışabilir.

•	Güvenlik Açıkları 

•	Yasal Engeller: Bilişim hizmetini kullanan firmanın ülkesinden farklı bir ülkede depolanması halinde, bu ülkeler arasında veri güvenliği ve gizliliği başta olmak üzere var olan yasal farklılıklar sorunlar oluşturabilir. Birçok ülkede veri gizliliği ile ilgili yasalardan dolayı verilerin nerede saklandığı oldukça önemli bir konudur. [7][8][17]

10.İLGİLİ ÇALIŞMALAR (DEMO)
Özet
Günümüzde yaygın olarak kullanılan Java dili, iş parçacıklarının yönetilmesi için kullanılan kütüphaneleri ile paralel uygulamaların geliştirilmesine destek sağlar. Sunulan çalışmada AWT üzerinden 72 ve 36 çekirdekli sanal makine ile 4 ve 8 çekirdekli bilgisayarlarımız üzerinde, matris işlemleriyle ilgili birçok uygulamada temel oluşturan matris çarpma algoritmasının Java dili kullanılarak paralel gerçeklenmesi karşılaştırılmıştır. Yapılan incelemelerimizle, iş parçacığı adedi ve 8000x8000 matris boyutunun paralel hesaplama ile Java dili ile gerçeklenmiş paralel matris çarpma algoritmasının çok çekirdekli bilgisayar üzerinde hızlandırma ve verimlilik sağladığı grafiksel veriler elde edilmiştir.
10.1 Paralel Matris Çarpma Algoritmasının Çok Çekirdekli Makineler Üzerinde Java İş Parçacıkları İle Analizi
Yüksek hesaplama gücü gerektiren uygulamalarda yüksek hızlı işlemci kullanmaya alternatif olarak, algoritmayı aynı anda farklı çekirdekler üzerinde çalıştırmak ve böylece uygulamaların hızını artırmak etkili yöntemlerdendir. Paralel hesaplamada hız kazancı, hesaplama yükünün küçük parçalara bölünerek her bir parçanın aynı anda işletilmesiyle sağlanır.
Çok çekirdekli işlemciye sahip bir bilgisayarda işletim sistemi birden fazla programı çekirdeklere dağıtarak aynı anda yürütebilir. Bu sebeple, birbirinden farklı görevler yürütmek için aynı proses içinde tanımlanabilen iş parçacıkları donanımın birden fazla işlemciye sahip olduğu durumlarda paralel hesaplama için kullanılmaktadır.
Çarpımı gerçekleştirilecek matrisler iş parçacıkları arasında ortak kullanılarak her bir iş parçacığı ayrılan işlem yükünü matrisin ilgili elemanlarını kullanarak gerçekleştirebilir. Paralel matris çarpma işleminde kullanılan çekirdek adedi arttıkça elde edilecek hızlandırma miktarının da aynı oranda artması beklenir.
Sunulan çalışmada, çok çekirdekli bilgisayarlar üzerinde Java yazılımı kullanılarak hızlandırma ve paralel verimlilik, iş parçacığı adedi ve matris boyutlarına bağlı olarak incelenmiştir.



10.2 Gerçekleştirilen Testler ve Değerlendirmeler
MAKİNE ADI	ÖZELLİK	ÇALIŞMA SÜRESİ (dakika)
Lenovo	4 Çekirdek	42 
Lenovo	8 Çekirdek	24 
C5n.9xlarge	36 Çekirdek, 96 GB Ram	8,5
C5n.18xlarge	72 Çekirdek,192 GB Ram	4
                                                                                
                          			 	          
10.3 Sonuç
Gerçekleştirilen testler ve değerlendirmeler sonucunda matris çarpma işleminin hızlandırılması çok çekirdekli makinalarla doğru orantılıdır. Bu sebeple kişisel bilgisayarlarımıza kıyasla AWS tarafından kiralanan daha performanslı makinaların buna dayalı yürütülecek algoritmaların da performansını artırdığı yapılan bu demo ile kanıtlanmıştır.
KAYNAKÇA
1.	https://searchcloudcomputing.techtarget.com/definition/cloud-computing
2.	https://www.investopedia.com/terms/c/cloud-computing.asp
3.	https://www.fastmetrics.com/blog/tech/what-is-cloud-computing/
4.	https://www.endustri40.com/bulut-bilisim-cloud-computing-nedir/
5.	https://blog.codevist.com/bulut-bilisim-be8173a9234d
6.	https://www.bilginc.com/tr/egitim-haber/cloud-computing-nedir
7.	https://www.timurdemir.com.tr/bulut-bilisim-cloud-computing-nedir/
8.	https://azure.microsoft.com/tr-tr/overview/what-is-cloud-computing/
9.	https://blog.natro.com/cloud-computing-nedir/
10.	https://www.cemaltaner.com.tr/2018/07/12/bulut-bilisim-cloud-computing-nedir/
11.	https://www.youtube.com/watch?v=1KwpE20VxPU
12.	https://www.maxihaber.net/bulut-bilisim-cloud-computing-nedir/
13.	https://shiftdelete.net/herkes-icin-cloud-computing-rehberi-1-20343
14.	https://www.olkando.com/bulut-teknolojisi-cloud-computing-nedir/
15.	https://radore.com/blog/bulut-bilisim-cloud-computing-konuk-yazar.html
16.	http://www.hakanuzuner.com/index.php/cloud-computing.html
17.	https://www.tech-worm.com/bulut-teknolojisi-nedir-cesitleri-kullanim-alanlari-faydalari-nelerdir/
18.	https://proente.com/bulut-teknolojisi-neler-getirdi/
19.	https://www.salesforcetutorial.com/introduction-to-cloud-computing/
20.	http://cloudcomputingnet.com/cloud-computing-architecture/
21.	https://jelecos.com/company/multi-cloud-mean-hybrid-cloud/




