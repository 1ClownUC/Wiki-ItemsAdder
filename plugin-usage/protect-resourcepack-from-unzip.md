# 🚨 Защита ваших текстур

{% hint style="info" %}
С недавних пор, при помощи ItemsAdder вы можете защитить все свои творения от распоковки и воровства.  
Включите данную фунцию в основном файле конфигурации config.yml и перепакуйте свой пакет ресурсов при помощи команды /iazip.  
Если вы используете Dropbox в качестве хоста текстур - не забывайте перезалить его и обновить ссылку на него в файле конфигурации config.yml

Используйте эту строку, чтобы включить:

```yaml
  zip:
    protect-file-from-unzip:
      enabled: true
      extreme: true
```
{% endhint %}

### enabled

The `enabled` property allows you to protect the resourcepack with a basic method.

### extreme

The `extreme` property allows you to protect the pack with another layer of protection to block some other methods to unzip the pack.

## Showcase

Небольшой мем, который показывает, как пользователь пытается украсть ваш пакет ресурсов, но внутри видит лишь битые файлы и папки, весом в 0 килобайт.

{% embed url="https://youtu.be/MhtEhoOuWV8" %}

