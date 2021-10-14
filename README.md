# MongoDB-ControlPanel
## Mongodb Monitoring and Managing Software

PyMongo kütüphanesi ve flask çatısı ve websocket kullanarak oluşturulmuş bir kontrol panel.

### Yetenekleri


* MongoDb nin network, memory, operationlarını anlık olarak izler ve canvasjs yardımıyla grafiğe döker.
* Kullanıcı oluşturur.
* Connection listesini tablo şeklinde sunar. 
* Document ve collectionları görüntüler. 
* Collectionları siler. 
* Global ve setwarning Loglarını websocket yardımıyla görüntüler.

### Kurulum

```sh
pip3 install -r requirements.txt
```

Init Dosyası Düzenleyin

```
mongo_client = MongoClient('mongodb://xxx.xx.x.xx:27017/')

```

Gerekli düzenlemeleri yaptıktan sonra projeyi çalıştırın

```sh
python3 run.py
```


###  Giriş Ekranı
![Login Page](docs/giriş.png)

###  Monitor Ekranı
![Dashborad Page](docs/dashborad.png)

###  Log Ekranı
![Log Page](docs/log.png)

### Kullanıcı Ekleme Ekranı
![User Page](docs/user.png)





