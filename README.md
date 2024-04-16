# HL7-Message-Transfering
# Iguana Client Example

Bu, Interfaceware'in Iguana platformunda bir istemci uygulaması örneğidir. Bu kod, Iguana platformu üzerinde çalışan bir sunucuya HL7 mesajı gönderir ve gelen yanıtı alır.

## Kullanım

1. Proje dosyalarınızı bu depoya ekleyin.
2. `interfaceware_client` kütüphanesini yükleyin (varsa).
3. Kodunuzda `IguanaClient` ve `Message` sınıflarını kullanarak Iguana sunucusuna mesaj gönderme ve almayı gerçekleştirin.
4. Kodunuzu çalıştırın ve Iguana sunucusuyla iletişim kurmayı sağlayın.

## Kod Açıklaması

- `iguana_client_example.py`: Ana Python kodu. Iguana sunucusuna bağlanmayı, bir HL7 mesajı göndermeyi ve gelen yanıtı almayı sağlar.
- `requirements.txt`: Gerekli kütüphaneleri içeren dosya.
- `LICENSE`: Projenin lisans bilgilerini içeren dosya.

## Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız olacaktır:

- `interfaceware_client`
- (varsa) Diğer bağımlılıklar

Gerekli kütüphaneleri yüklemek için terminal veya komut istemcisinde aşağıdaki komutu çalıştırabilirsiniz:
pip install -r requirements.txt
