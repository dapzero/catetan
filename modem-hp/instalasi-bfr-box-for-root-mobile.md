# 📝 Instalasi 📦 BFR (Box for Root) Mobile

<details>

<summary>Syarat</summary>

* Terpasang magisk

</details>

### 1) BAHAN

* Tema Dashboard Yacd | [Link](https://t.me/taamarin/283465/391342)
* Clash Core | [Link](https://github.com/MetaCubeX/mihomo/releases)
* Module Magisk BFR | [Link](https://github.com/taamarin/box_for_magisk/releases)
* Module Magisk Web UI BFR | [Link](https://github.com/geeks121/webui_bfm/releases)

***

### 2) STEP INSTAL

{% stepper %}
{% step %}
Pilih versi <mark style="color:green;">Latest</mark>, download _**module BFR**_ & _**WEB UI BFR**_.
{% endstep %}

{% step %}
Pasang di Magisk kemudian reboot sistem.
{% endstep %}

{% step %}
Saat proses pemasangan module BFR, tekan tombol Power( + ) jika ada internet, sebaliknya tekan tombol Power ( - ) jika tidak ada internet.
{% endstep %}

{% step %}
Masuk ke `/data/adb/box/clash/` buat folder `dashboard`, jika sudah ada selanjutnya download _**Tema Dashboard Yacd**_, extract dan copy paste semua file ke `/data/adb/box/clash/dashboard`.
{% endstep %}

{% step %}
Sebelum mendownload _**Clash Core**_, check sistem HP memakai [apk Device Info](https://play.google.com/store/apps/details?id=com.ytheekshana.deviceinfo),

<figure><img src="../.gitbook/assets/arch-phone.png" alt="" width="267"><figcaption><p>Contoh arch 64bit</p></figcaption></figure>
{% endstep %}

{% step %}
Jika `32bit pilih mihomo-android-armv7` atau `64bit pilih mihomo-arm64-v8`.
{% endstep %}

{% step %}
Download _**Clash Core**_ pilih sesuai sistem HP dan disarankan versi <mark style="color:green;">Latest</mark>, extract dan paste di `data/adb/box/bin/xclash`, ubah nama-nya jadi `mihomo`.
{% endstep %}
{% endstepper %}

***

### 3) FIX ERROR

{% hint style="info" %}
* <mark style="color:red;">Error blank putih</mark>
* <mark style="color:red;">Error 404 not found</mark>
* <mark style="color:red;">Error halaman login Yacd / Dashboard blank putih</mark>



{% stepper %}
{% step %}
Update apk WebView terbaru | [Link](https://play.google.com/store/apps/details?id=com.google.android.webview)
{% endstep %}

{% step %}
Open config.yaml <mark style="color:orange;">(untuk clash)</mark> / config.json <mark style="color:orange;">(untuk sing-box)</mark>, samakan kode-nya

{% code title="config.yaml" overflow="wrap" lineNumbers="true" %}
```yaml
#clash
external-controller: 0.0.0.0:9090
external-ui: /data/adb/box/clash/dashboard
#secret: ""
```
{% endcode %}

{% code title="config.json" overflow="wrap" lineNumbers="true" %}
```json
#sing-box
"experimental": {
    "clash_api": {
        "external_controller": "0.0.0.0:9090",
        "external_ui": "/data/adb/box/sing-box/dashboard",
        "cache_file": "cache.db",
        "store_selected": true
    }
}
```
{% endcode %}
{% endstep %}

{% step %}
Bersihkan cache app/browser.
{% endstep %}

{% step %}
Gunakan browser terbaru seperti Chrome, Firefox, Kiwi, dll.
{% endstep %}
{% endstepper %}
{% endhint %}

{% hint style="info" %}
* <mark style="color:red;">Clash Version Information Not Available</mark> ([Contoh Error](https://t.me/taamarin/283465/391261))



{% stepper %}
{% step %}
Download _**Clash Meta**_ | [Link](https://github.com/MetaCubeX/Clash.Meta)
{% endstep %}

{% step %}
Extract & ganti nama jadi <mark style="color:orange;">clash\_meta</mark>
{% endstep %}

{% step %}
Paste di `/data/adb/box/bin`
{% endstep %}
{% endstepper %}
{% endhint %}

***

### 4) Daftar Pustaka

1. Una. (2024, 13 Juli). Telegram. Diakses pada 9 Agustus 2024, dari https://t.me/taamarin/360987.
2. taamarin. (2023). box\_for\_magisk. github.com. Diakses pada 13 Agustus 2024, dari https://github.com/taamarin/box\_for\_magisk.
3. geeks121. (2024). webui\_bfm. github.com. Diakses pada 13 Agustus 2024, dari https://github.com/geeks121/webui\_bfm.
4. MetaCubeX. (2021). mihomo. github.com. Diakses pada 13 Agustus 2024, dari https://github.com/MetaCubeX/mihomo.

***

