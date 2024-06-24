# Nubit

> Nubit'te ilerleyen günlerde farklı gelişmeler olacak

> Şimdilik node kuruyoruz sadece.

> Cüzdanımız ile bağlanıyoruz [buradan](https://alpha.nubit.org/) 

> Herhangi bir sunucuya bu komutları giriyoruz: 

`screen -S nubit`
`curl -sL1 https://nubit.sh | bash`

> Loglarrımız arasındaki keyleri kaydediyoruz.
> Kaydettikten sonra ctrl a+d ile screenden çıkıyoruz.

![image](https://github.com/ruesandora/Nubit/assets/101149671/2ef4e7cd-7d50-42e7-9864-23f20399bb17)

> Pubkey'i 15 dakika sonra verify ediyoruz, totalde 6k puanımızı alıyoruz.

<img width="622" alt="Ekran Resmi 2024-06-24 17 22 44" src="https://github.com/ruesandora/Nubit/assets/101149671/f81d1cf5-139a-413c-a830-ef00b42c0339">

## 

-  Eğer ekran çok hızlı geçtiyse pubkey'inizi görmek için (screen dışında deneyin)

```sh
 $HOME/nubit-node/bin/nkey list --p2p.network nubit-alphatestnet-1 --node.type light
```

> **key: yazan kısmı siteye girin.
 address: yazan kısım da sizin nubit adresinizdir.**
 
 ##

-  Adresinizin kurtarma tümceciklerini (mnemonic) görmek için ise:

```sh
nano $HOME/nubit-node/mnemonic.txt
```

