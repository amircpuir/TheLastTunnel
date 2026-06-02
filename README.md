# TheLastTunnel
برای نصب و دسترسی دادن به فایل : 
```bash
wget -O /root/TheLastTunnel.bin https://github.com/amircpuir/TheLastTunnel/raw/main/thelasttunnel && chmod +x /root/TheLastTunnel.bin
```
ران کردن برنامه : 
```bash
sudo ./TheLastTunnel.bin

```

از شما یه رنج پورت برای کانکشن های خود تانل میخاد که ربطی به پورت کانفیگ نداره رنج رو برای مثال
```
30000-30100
```

مشاهده وضعیتِ لحظه‌ای سرویس:

```bash
sudo systemctl status amirtunnel.service
```
توقفِ کاملِ تانل (مثلاً برای تغییر تنظیمات):

```bash
sudo systemctl stop amirtunnel.service
```
استارت مجددِ تانل:

```bash
sudo systemctl start amirtunnel.service
```
ریستارت کردنِ تانل (بعد از هر تغییری):

```bash
sudo systemctl restart amirtunnel.service
```


Channel: @Telhost1
