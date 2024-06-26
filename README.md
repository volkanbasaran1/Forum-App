![ekran](https://github.com/volkanbasaran1/Forum-App/assets/76842256/30880022-564e-472b-b775-8e8c5ef3014b)
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Proje Dokümantasyonu</h1>
    <p>Bu proje, modern web uygulamalarının geliştirilmesinde yaygın olarak kullanılan Model-View-Controller (MVC) mimari yapısını takip eder.</p>
    <h2>Kütüphaneler</h2>
    <ul>
        <li><strong>axios:</strong> HTTP istekleri yapmak için kullanılır.</li>
        <li><strong>react-router-dom:</strong> SPA (Tek Sayfa Uygulaması) yönlendirmeleri için kullanılır.</li>
        <li><strong>json-server:</strong> Mock REST API oluşturmak için kullanılır.</li>
        <li><strong>tailwind:</strong> CSS framework'ü olarak kullanılır, hızlı ve duyarlı tasarımlar yapmayı sağlar.</li>
    </ul>
    <h2>MVC (Model - View - Controller)</h2>
    <h3>Model:</h3>
    <p>Uygulamanın veri mantığını veya yapısını temsil eder. Örneğin:</p>
    <ul>
        <li>Bileşende tutulacak state'in başlangıç değeri</li>
        <li>Veriyi formatlamaya yarayan fonksiyonlar</li>
        <li>API işlemleri burada tutulabilir</li>
    </ul>
    <h3>View:</h3>
    <p>Son kullanıcının gördüğü tasarımdır. Bileşenlerimizdeki return satırında yazdığımız JSX elemanları bu bölümde tanımlanır.</p>
    <h3>Controller:</h3>
    <p>View ile model arasındaki bağlantıyı sağlar. Kullanıcı etkileşimiyle tetiklenecek bütün fonksiyonlar burada tanımlanır.</p>
    <h2>MVC Klasör Yapısı</h2>
    <h3>1. Yol</h3>
    <pre><code>- public
- src
  - pages
    - MainPage
      - MainPageController
      - MainPageView
      - MainPageModel
    - Auth
      - AuthPageController
      - AuthPageView
      - AuthPageModel
</code></pre>

    <h3>2. Yol</h3>
    <pre><code>- public
- src
  - models
    - MainPageModel
    - AuthPageModel
  - views
    - MainPageView
    - AuthPageView
  - controllers
    - MainPageController
    - AuthPageController
</code></pre>

    <h2>Katkıda Bulunma</h2>
    <p>Projeye katkıda bulunmak istiyorsanız, lütfen öncelikle bir issue oluşturarak hangi konuda yardımcı olmak istediğinizi belirtin.</p>

    <h2>Lisans</h2>
    <p>Bu proje MIT lisansı altında lisanslanmıştır. Daha fazla bilgi için projenin <code>LICENSE</code> dosyasına bakın.</p>
</body>
</html>
