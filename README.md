# TheLastTunnel
برای نصب و دسترسی دادن به فایل : 
```bash
wget -O /root/TheLastTunnel.bin https://github.com/amircpuir/TheLastTunnel/raw/main/thelasttunnel && chmod +x /root/TheLastTunnel.bin
```
ران کردن برنامه : 
```bash
sudo ./thelasttunnel
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
