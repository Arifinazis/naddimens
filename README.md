<p align="center">
  <img src="https://github.com/Arifinazis/naddimens/raw/main/logo.png" alt="naddimens Logo" width="120" height="120"/>
</p>

<h1 align="center">naddimens</h1>

<p align="center">
  Resource-only library for scalable Android UI development.
</p>

<p align="center">
  <a href="https://jitpack.io/#Arifinazis/naddimens"><img src="https://jitpack.io/v/Arifinazis/naddimens.svg" alt="JitPack"></a>
  <a href="https://www.paypal.com/paypalme/Arifinazis"><img src="https://img.shields.io/badge/Donate-PayPal-blue.svg" alt="Donate Paypal"></a>
</p>

---

## 📦 Integrasi

Tambahkan repository JitPack di `settings.gradle` project kamu:

```gradle
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

Lalu tambahkan dependency di `build.gradle` aplikasi:

```gradle
dependencies {
    implementation 'com.github.Arifinazis:naddimens:v1.0.0'
}
```

---

## 🚀 Fitur Utama

- ✅ Hanya resource (dimens) tanpa kode Java/Kotlin.
- ✅ Super ringan: cepat di-build dan hemat ukuran APK/AAB.
- ✅ Struktur standar dan konsisten untuk skalabilitas UI.
- ✅ Dukungan penuh AndroidX dan Material Design 3.
- ✅ Siap digunakan untuk project pribadi atau production app.

---

## 🛠️ Penggunaan

Setelah mengintegrasikan `naddimens`, kamu bisa langsung menggunakan resource-nya:

**Contoh penggunaan dimens:**

```xml
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Hello World"
    android:textSize="@dimen/text_m"
    android:layout_margin="@dimen/margin_medium"
    android:padding="@dimen/padding_small" />
```
## 📋 Struktur Resource

| Folder | Keterangan |
|:---|:---|
| `values/dimens.xml` | Ukuran-ukuran standar (padding, margin, radius, elevation, text size) |
---

## ✨ Roadmap

- [x] Initial Release v1.0.0
- [ ] Tambah varian dimens untuk tablet & large screen
---

## ❤️ Dukungan

Jika library ini bermanfaat untuk kamu, pertimbangkan untuk mendukung pengembangan lebih lanjut:

<p align="center">
  <a href="https://www.paypal.com/paypalme/Arifinazis">
    <img src="https://img.shields.io/badge/Donate-PayPal-blue.svg" alt="Donate Paypal"/>
  </a>
</p>

---

## 👤 Pembuat

Developed with ❤️ by [Arifinazis](https://github.com/Arifinazis)

---

## 📜 Lisensi

MIT License

Copyright (c) 2024 Arifinazis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
