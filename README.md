# beebeeeğimmmmm

  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Feyza İçin</title>
  <meta name="description" content="Romantik bir dijital hediye sayfası." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Quicksand:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0a0a12;
      --accent:#ff5f85;
      --muted:#f2f2f2b3;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{
      font-family:'Quicksand',sans-serif;
      background:radial-gradient(circle at 20% 20%,rgba(255,95,133,0.08),transparent),var(--bg);
      color:#fff;
      min-height:100vh;
      display:flex;
      flex-direction:column;
      align-items:center;
      padding:20px;
      text-align:center;
      overflow-x:hidden;
    }
    h1{
      font-family:'Playfair Display',serif;
      font-size:clamp(26px,6vw,40px);
      color:var(--accent);
      margin:40px 0 20px;
      letter-spacing:0.5px;
      position:relative;
      z-index:2;
    }
    .poems{
      display:grid;
      gap:20px;
      max-width:700px;
      width:100%;
      z-index:2;
      position:relative;
    }
    .poem{
      background:rgba(255,255,255,0.05);
      border-radius:16px;
      padding:18px 20px;
      line-height:1.7;
      font-size:17px;
      backdrop-filter:blur(6px);
      box-shadow:0 0 20px rgba(255,95,133,0.08);
      transition:transform .3s ease,box-shadow .3s ease;
      white-space:pre-line;
    }
    .poem:hover{
      transform:translateY(-3px);
      box-shadow:0 8px 20px rgba(255,95,133,0.18);
    }
    .poem::before{
      content:'❤';
      display:block;
      font-size:18px;
      color:var(--accent);
      margin-bottom:10px;
      opacity:0.8;
    }
    footer{
      margin:40px 0 20px;
      font-size:14px;
      color:var(--muted);
      z-index:2;
      position:relative;
    }

    .heart{
      position:fixed;
      bottom:-20px;
      font-size:20px;
      color:var(--accent);
      animation:float 6s linear forwards;
      opacity:0.8;
      z-index:1;
      pointer-events:none;
    }
    @keyframes float{
      0%{transform:translateY(0) scale(1);opacity:1;}
      100%{transform:translateY(-110vh) scale(1.5);opacity:0;}
    }

    @media (max-width:600px){
      body{padding:16px;}
      .poem{font-size:16px;padding:14px 16px;}
    }
  </style>
</head>
<body>
  <h1>Feyza İçin Yazılan Şiirler</h1>
  <div class="poems">
    <div class="poem"> “SENİNLE BAŞLAYAN HER ŞEY”<br><br>Seninle başlayan her şey<br>gün ışığının perdeye ilk değdiği an kadar temiz…<br>Bazen adını söylemeden bile<br>içimde kocaman bir huzur büyüyor.<br>Sanki dünya yorulsa bile<br>senin sesin yeniden kuruyor kalbimi.<br><br>Biliyor musun sevgilim,<br>senin varlığın<br>çaydan önceki sıcak su gibi—<br>henüz hiçbir şey eklenmemiş<br>ama yine de içimi ısıtan bir bütünlük taşıyor.<br><br>Ben seni,<br>başımı omzuna yaslayınca<br>kendimi dünyaya ait hissedecek kadar<br>derinden sevdim.<br>Öyle ki,<br>senin olmadığın bir hayatı<br>düşünmek bile istemiyorum.<br><br>Ve inan,<br>sen bana ne kadar güveniyorsan<br>ben o güveni iki katı taşıyorum içimde.<br>Kalbim yorulmaz senden;<br>çünkü sen benim en duru gerçeğimsin.</div>

    <div class="poem"> “KALBİMDEKİ SESSİZ ŞEHİR”<br><br>Kalbimde bir şehir kurdum—<br>sokaklarında sen yürüyorsun.<br>Her köşesinde gülüşün asılı,<br>her evin içinde adın var.<br>Bazen kalabalık olur dünya,<br>gürültülü, yorucu…<br>ama ben içimdeki o sessiz şehre<br>sığıyorum ve orada seninleyim.<br><br>Seni sevmek,<br>yeni bir günün başlaması gibi<br>kaçınılmaz ve güzel.<br>Hiçbir şeye bağlı olmayan<br>temiz bir başlangıç…<br><br>Sen olmasan,<br>yüreğim yarım kalmış bir roman gibi olurdu.<br>Ama sen geldin,<br>bütün eksik sayfalarımı tamamladın.<br><br>Ve bil sevgilim,<br>ben sana karşı daima<br>en dürüst, en sakınmasız,<br>en gerçek hâlimle duruyorum.</div>

    <div class="poem"> “SANA YAZILAN EN UZUN NİYET”<br><br>Bir niyet tuttum içimde:<br>Sana hep iyi gelmek.<br>İyi bakmak kalbine,<br>iyi davranmak yüreğine,<br>iyi sarılmak omzuna…<br>Benim sana sevgim<br>bir telaş değil;<br>bir ömür kararlılığı.<br><br>Seni düşündüğüm her defa<br>kalbim sessizce “iyi ki” diyor.<br>Ve bilirsin,<br>hiçbir “iyi ki” boşuna değildir.<br>Benimki de değil.<br><br>Ne olursa olsun,<br>dünyanın tüm gölgeleri toplansa bile<br>ben senin ışığına sığınırım.<br>Çünkü sen,<br>tutunmam gereken en gerçek şeysin.</div>

    <div class="poem"> “SENİNLE TAMAMLANAN YARIMIM”<br><br>Her insan biraz eksiktir ya doğarken…<br>Benim eksikliğim<br>sen gelince tamamlandı.<br>Gülüşünde tamamlandım,<br>adında, sesinde,<br>bana uzanan o ince iyi niyetinde.<br><br>Korkularım bile<br>seninle daha az ürkütüyor beni.<br>Çünkü içimde biri fısıldıyor:<br>“Yanında o var, korkma.”<br><br>Ben seni saklamıyorum sevgilim,<br>gizlemiyorum,<br>küçük bir sevda gibi taşımıyorum.<br>Tertemiz bir gururla seviyorum.</div>

    <div class="poem"> “SENİNLE YENİDEN DOĞAN İÇİM”<br><br>Her sabah uyandığımda<br>aklıma düşen ilk şey sensin.<br>Yorgun uyanmış olsam bile<br>adını düşününce toparlanıyorum.<br>Sanki içimde biri<br>yeniden düğmeliyor gömleğini,<br>yeniden topluyor dağınıklığını.<br><br>Seni sevmek,<br>insanın içini tazeleyen bir bahar gibi.<br>Ve ben bu bahara<br>hiç doyamıyorum.<br><br>Sen olmasan,<br>içimdeki güneş eksik doğardı.<br>Ama sen varsın…<br>ve ben her gün yeniden<br>seninle aydınlanıyorum.</div>

    <div class="poem"> “SESSİZCE BÜYÜYEN AŞKIM”<br><br>Senin hakkındaki en güzel şey,<br>seni düşündüğümde içimde<br>kendiliğinden büyüyen huzur.<br>Ne bağırır,<br>ne çağırır,<br>ne çarpar…<br>Sadece büyür sessizce.<br><br>Bir çiçeğin ışığa yönelişi gibi<br>benim kalbim de sana yöneliyor.<br>Zorla değil,<br>zorunlulukla değil—<br>doğasıyla.<br><br>Ben seni sevdikçe<br>daha iyi biri oluyorum.<br>Ve bu dünyanın karmaşasında<br>sen benim en sade cevabım oluyorsun.</div>

    <div class="poem"> “SENİNLE DURULAN ZAMAN”<br><br>Ne zaman yorulsam,<br>aklıma sen geliyorsun<br>ve zaman duruluyor içimde.<br>Sanki kalbimin içinde<br>bir su sessizce berraklaşıyor.<br>Senin yüzünden değil,<br>seninle.<br><br>Seni sevmek,<br>kendini iyileştiren bir şiir gibi.<br>Okudukça hafifliyorum.<br><br>Ve bil ki,<br>benim sana olan sadakatim<br>bir seçim değil,<br>bir sonuç:<br>Kalbim seni seçmiş bir kere,<br>geri dönüşü yok.</div>

    <div class="poem"> “EN TEMİZ YERİME YAZDIM SENİ”<br><br>İçimde herkesin bilmediği<br>küçük bir yer var.<br>Sessiz, derin,<br>kimsenin elini süremediği…<br>İşte oraya yazdım adını.<br>Silmeye çalışsam bile<br>izleri kalır artık.<br><br>Sen bana<br>hiç kimsenin hissettiremediği bir iç huzur verdin.<br>Bu yüzden güveniyorum sana—<br>çünkü ruhuma değen insan<br>kolay unutulmaz.<br><br>Ve ben seni<br>unutulmazlığın en zarif hâliyle sevdim.</div>

    <div class="poem"> “KADERİN EN GÜZEL YORUMU”<br><br>Bazen düşünüyorum da,<br>sen benim kaderimin<br>en güzel yorumu olmalısın.<br>Bir insanın yaşamına<br>bu kadar iyi gelmesi,<br>bu kadar derin iz bırakması<br>tesadüf olamaz.<br><br>Sana baktığımda<br>kendimi daha iyi tanıyorum.<br>Ve biliyorum ki<br>sana sadakatim<br>bir zorunluluk değil—<br>bir minnet.<br>Kalbim senin yanında<br>kendini evinde hissediyor.</div>

    <div class="poem"> “KALBİMİN TEK YÖNÜ”<br><br>Her yollar karıştığında<br>tek bildiğim yön sensin.<br>Ne pusula isterim,<br>ne harita,<br>ne tavsiye…<br>Kalbim seni gösteriyor tek bir çizgiyle:<br>“Buraya dön.”<br><br>Gülüşünle başlayan,<br>bakışınla devam eden<br>uzun bir yol bu…<br>Dönmek istemediğim,<br>bırakmak istemediğim bir yol.<br><br>Ve bil sevgilim—<br>ben seni öyle sevdim ki,<br>bütün ihtimalleri susturup<br>kalbimi tek bir ihtimale bağladım:<br>Sen.</div>
  </div>
  <footer>Bu sayfa sadece senin için hazırlandı, Feyza.</footer>
  <script>
    function createHeart(){
      const heart=document.createElement('div');
      heart.className='heart';
      heart.textContent='❤';
      heart.style.left=Math.random()*100+'vw';
      heart.style.fontSize=(16+Math.random()*24)+'px';
      heart.style.animationDuration=(5+Math.random()*4)+'s';
      document.body.appendChild(heart);
      setTimeout(()=>heart.remove(),8000);
    }
    setInterval(createHeart,500);
  </script>


