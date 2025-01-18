## Удаление системных приложений с помощью Canta  
**Canta** — это удобное и мощное приложение для удаления любых приложений на вашем телефоне, включая системные. Оно анализирует каждое приложение и отображает, можно ли его безопасно удалить.  

Для работы **Canta** требуется установленное приложение **Shizuku**, которое предоставляет привилегии для работы с системными компонентами без необходимости рут-прав.  

### Ссылки:  
- [Canta на GitHub](https://github.com/samolego/Canta)  
- [Shizuku в Google Play](https://play.google.com/store/apps/details?id=moe.shizuku.privileged.api)

## Ручное удаление приложений


### Knox
Это платформа безопасности для устройств Samsung, предназначенная для защиты данных и обеспечения корпоративного управления. Она включает функции шифрования, безопасных контейнеров и управления устройствами, используемыми в бизнес-среде.

```
adb shell pm uninstall --user 0 com.samsung.android.knox.containeragent
adb shell pm uninstall --user 0 com.samsung.android.knox.analytics.uploader
adb shell pm uninstall --user 0 com.sec.enterprise.knox.cloudmdm.smdms
adb shell pm uninstall --user 0 com.samsung.android.knox.attestation
adb shell pm uninstall --user 0 com.sec.enterprise.knox.attestation
adb shell pm uninstall --user 0 com.samsung.android.knox.containercore
adb shell pm uninstall --user 0 com.samsung.knox.securefolder
adb shell pm uninstall --user 0 com.samsung.android.bbc.bbcagent
adb shell pm uninstall --user 0 com.android.managedprovisioning
adb shell pm uninstall --user 0 com.samsung.knox.keychain
adb shell pm uninstall --user 0 com.knox.vpn.proxyhandler
adb shell pm uninstall --user 0 com.samsung.ucs.agent.ese
adb shell pm uninstall --user 0 com.samsung.android.knox.pushmanager
```

### Facebook
Популярная социальная сеть с рядом приложений для взаимодействия, общения и получения уведомлений. Удаление этих компонентов исключает возможность использования социальной сети и интеграции с системными функциями устройства.

```
adb shell pm uninstall --user 0 com.facebook.appmanager
adb shell pm uninstall --user 0 com.facebook.katana
adb shell pm uninstall --user 0 com.facebook.services
adb shell pm uninstall --user 0 com.facebook.system
```
