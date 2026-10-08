# dijitaldusler.com

Dijital Düşler'in tanıtım sitesi. Tek dosya: `index.html`. Derleme gerekmez.

## GitHub'a koyma

1. GitHub'da yeni bir depo aç: `dijitaldusler-site`
2. Bu klasördeki dosyaları depoya yükle (`index.html`, `README.md`).

## Coolify ile yayına alma

1. Coolify → **+ New Resource** → GitHub deposunu seç.
2. Build Pack: **Static**.
3. Publish directory: `/`
4. Domains: `https://dijitaldusler.com` ve `https://www.dijitaldusler.com`
5. **Deploy**. SSL sertifikasını Coolify kendisi alır.

## DNS kayıtları (alan adını aldığın firmada)

| Tür | Ad  | Değer               |
|-----|-----|---------------------|
| A   | @   | sunucunun IP adresi |
| A   | www | sunucunun IP adresi |

Bundan sonra GitHub'a her yüklemede site güncellenir (Coolify'da otomatik deploy açıksa).
