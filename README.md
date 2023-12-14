# MyMacChanger
MyMacChanger, basit bir Python betiği olan bir araçtır ve ağ arayüzünün MAC adresini değiştirmek için kullanılır. Bu aracı kullanarak, ağ güvenliği testleri yapabilir veya gizliliğinizi artırabilirsiniz.

## Kullanım

1. **Başlamadan Önce:**
   - Sistem üzerinde Python 3.6 veya üstü yüklü olmalıdır.

2. **Kodu Çalıştırma:**
   - Terminal veya komut istemcisine şu komutu girerek aracı kullanabilirsiniz:
     ```bash
     python Mac_Changer.py -interface eth0 -mac [Yeni MAC Adresi]
     ```
     Örneğin:
     ```bash
     python Mac_Changer.py -i eth0 -m 00:11:22:33:44:55
     ```

3. **Sonuçları Kontrol Etme:**
   - MAC adresini değiştirdikten sonra, değişikliğin başarıyla gerçekleşip gerçekleşmediğini kontrol etmek için aşağıdaki komutu kullanabilirsiniz:
     ```bash
     ifconfig [Arayüz]
     ```

## Notlar

- Bu aracı kullanırken sorumlu olun ve yalnızca sahip olduğunuz cihazlarda deneme yapın.
- MAC adresini değiştirmek, ağ bağlantınızı etkileyebilir.

## Lisans

Bu proje, MIT Lisansı ile lisanslanmıştır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.
