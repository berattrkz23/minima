 # Bu komutu giriyoruz. Tabii ki sunucumuzu update upgrade yapmayı unutmayalım.
```
wget -O minima_setup.sh https://raw.githubusercontent.com/minima-global/Minima/master/scripts/minima_setup.sh && chmod +x minima_setup.sh && sudo ./minima_setup.sh -r 9002 -p 9001
```

#  Minima Global sitesine girip üyelik oluşturuyoruz daha sonrasında hesabımıza giriş yapıyoruz:
Girdikten sonra en üstte bulunan Incentive IDyi kopyalıyoruz hazır dursun;

https://incentive.minima.global/account/register)

Şimdi vereceğim koddaki XXXXX yazan kısma yukarıda üyelik açıp aldığınız kendi Incentive ID nizi yazmalısınız. Tekrardan siyah ekrana dönüp CTRL + V ile yapıştırıyoruz ve biraz bekledikten sonra kurulum tamamdır, komut:
```
curl 127.0.0.1:9002/incentivecash+uid: XXXXXXXXXXX
```
sorularınız için instagram: s.berattrkz23
