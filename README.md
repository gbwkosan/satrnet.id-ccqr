## QR Code scanner for login hotspot MikroTik

### Cara Menggunakan

1. Tambahkan button di login.html

```html
<button
  onclick="window.location='https://bagussp99.github.io/satrnet.id-ccqr/';"
>
  QR Code
</button>
```

2. Tambahkan script berikut di MikroTik via Terminal.

```
/ip hotspot walled-garden ip

add action=accept comment="SatrNet.id QR Code Scanner" disabled=no dst-host=bagussp99.github.io
```

### Edited by [Satria](https://bagussp99.github.io/)
