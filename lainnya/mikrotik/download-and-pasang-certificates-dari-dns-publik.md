# 📌 Download & Pasang Certificates dari DNS Publik

## Download&#x20;

{% stepper %}
{% step %}
### Pakai firefox PC

<figure><img src="https://imgdlvr.com/pic/photocollage.com/20250208-6079/public" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
### Pilih USERTrust ECC -> Gulir kebawah -> Klik PEM (cert) -> Download

<figure><img src="https://imgdlvr.com/pic/photocollage.com/20250208-1562/public" alt=""><figcaption></figcaption></figure>
{% endstep %}
{% endstepper %}

## Upload Ke Mikrotik

{% stepper %}
{% step %}
### Masuk Mikrotik

Bagian Files -> Upload -> Caro {namaFile}.cert
{% endstep %}

{% step %}
### Ke System -> Certificates -> Import

<figure><img src="https://imgdlvr.com/pic/photocollage.com/20250208-0013/public" alt=""><figcaption><p>Contoh</p></figcaption></figure>
{% endstep %}
{% endstepper %}

***

Source:

1. Mikrotik wiki. [https://help.mikrotik.com/docs/spaces/ROS/pages/37748767/DNS#DNS-DNSoverHTTPS(DoH)](https://help.mikrotik.com/docs/spaces/ROS/pages/37748767/DNS#DNS-DNSoverHTTPS\(DoH\))
2. Youtube. [https://www.youtube.com/watch?v=w4erB0VzyIE](https://www.youtube.com/watch?v=w4erB0VzyIE)
3. Citraweb. [https://citraweb.com/artikel/390/](https://citraweb.com/artikel/390/)
