# Spotify Clone 🎶

Bu proje, Spotify API'sini kullanarak temel bir Spotify müzik çalar uygulaması geliştirmeyi amaçlamaktadır. Kullanıcılar Spotify hesapları ile giriş yapabilir ve çeşitli müzik bilgilerini görüntüleyebilir.

## Özellikler

- Spotify hesabı ile giriş yapma
- Kullanıcının en son dinledikleri şarkıları görme
- Çalma durumu ve çalma listesi bilgilerini görüntüleme
- Şarkıları oynatma ve duraklatma

## Canlı Demo

Projenin canlı demosuna [buradan](https://react-spotify-clonee.netlify.app/) ulaşabilirsiniz.

## Kullanılan Teknolojiler

- **React**: Kullanıcı arayüzünü oluşturmak için
- **Styled-components**: Bileşen tabanlı stil için
- **Spotify API**: Müzik verilerine erişim ve kontrol için
- **Netlify**: Projenin yayına alınması için

## Kurulum

Projeyi yerel ortamınızda çalıştırmak için şu adımları takip edebilirsiniz:

1. Projeyi klonlayın:
    ```bash
    git clone https://github.com/uzeyirdemiral/React-Spotify-Clone.git
    ```

2. Proje dizinine gidin:
    ```bash
    cd React-Spotify-Clone
    ```

3. Gerekli bağımlılıkları yükleyin:
    ```bash
    npm install
    ```

4. **Spotify Client ID ve Redirect URI'yi Güncelleyin:**
   - `src/components/Login.jsx` dosyasını açın ve aşağıdaki kısımları kendi bilgilerinize göre değiştirin:
     ```javascript
     const client_id = "your_spotify_client_id";
     const redirect_uri = "http://localhost:3000"; // veya Netlify adresiniz
     ```

5. Geliştirme sunucusunu başlatın:
    ```bash
    npm start
    ```

6. Tarayıcınızda [http://localhost:3000](http://localhost:3000) adresine giderek uygulamayı görüntüleyebilirsiniz.

## Kullanım

- **Spotify Bağlantısı**: Uygulamayı açtığınızda, **Connect Spotify** butonuna tıklayarak Spotify hesabınıza bağlanabilirsiniz.
- **Müzik Bilgisi Görüntüleme**: Giriş yaptıktan sonra kullanıcı bilgilerinizi, en son dinlediklerinizi ve mevcut çalma durumunuzu görebilirsiniz.


## Katkıda Bulunanlar

- **Üzeyir Demiral**

## Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına göz atabilirsiniz.
