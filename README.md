#MyMacChanger

MyMacChanger is a tool that is a simple Python script and is used to change the MAC address of the network interface. Using this tool, you can perform network security tests or increase your privacy.

## Use

1. **Before You Begin:**
   - Python 3.6 or higher must be installed on the system.

2. **Running the Code:**
   - You can use the tool by entering the following command in terminal or command prompt:
     ```bash
     python Mac_Changer.py -interface eth0 -mac [New MAC Address]
     ```
     For example:
     ```bash
     python Mac_Changer.py -i eth0 -m 00:11:22:33:44:55
     ```

3. **Checking Results:**
   - After changing the MAC address, you can use the following command to check whether the change took place successfully:
     ```bash
     ifconfig [Interface]
     ```

## Notes

- Be responsible when using this tool and only test it on devices you own.
- Changing the MAC address may affect your network connection.

## Licence

This project is licensed under the MIT License. See the [LICENSE] file for details.


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
