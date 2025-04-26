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

- ✅ Hanya resource (dimens, colors, styles) tanpa kode Java/Kotlin.
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

**Contoh penggunaan colors:**

```xml
<TextView
    android:textColor="@color/primary_text"
    android:text="Primary Text" />
```

---

## 📋 Struktur Resource

| Folder | Keterangan |
|:---|:---|
| `values/dimens.xml` | Ukuran-ukuran standar (padding, margin, radius, elevation, text size) |
| `values/colors.xml` | Warna standar untuk UI |
| `values/styles.xml` | Style default untuk komponen UI |

---

## ✨ Roadmap

- [x] Initial Release v1.0.0
- [ ] Support Dark Theme
- [ ] Tambah varian dimens untuk tablet & large screen
- [ ] Integrasi Material You dynamic color (Android 12+)

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

Lisensi akan segera diumumkan.
