<p align="center">
  <img alt="Rocketseat Education" src="https://avatars.githubusercontent.com/u/69590972?s=200&v=4" width="100px" />
</p>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=Rocketseat&message=Education&color=8257e5&labelColor=202024" alt="Rocketseat Project" />
  <a href="LICENSE"><img  src="https://img.shields.io/static/v1?label=License&message=MIT&color=8257e5&labelColor=202024" alt="License"></a>
</p>

## 💻 Projeto

igniteshoesapp

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">
  Feito com 💜 by Rocketseat
</p>

<!--START_SECTION:footer-->

<br />
<br />

<p align="center">
  <a href="https://discord.gg/rocketseat" target="_blank">
    <img align="center" src="https://storage.googleapis.com/golden-wind/comunidade/rodape.svg" alt="banner"/>
  </a>
</p>

<!--END_SECTION:footer-->

<br />

---

## Run app

To run with a physical device

```bash
  adb devices
```

```bash
  adb tcpip 5555
```

```bash
  adb connect deviceip:5555
```

## Install app on device and run (without expo-dev-clint)

```bash
  npx expo run:android
```

## Run with expo-dev-clint

```bash
  npx expo start --dev-client
```

## List schemes

```bash
  npx uri-scheme list
```

run test on android

```bash
  npx uri-scheme open igniteshoes://<deviceip>:8081 --android
```

testing navigation to product

```bash
  npx uri-scheme open igniteshoes://details/7 --android
```
