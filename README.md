# Cryptography (Kriptoloji)
----------------------------------------- English -----------------------------------------

What does Cryptography mean?

Cryptography involves creating written or generated codes that allow information to be kept secret. Cryptography converts data into a format that is unreadable for an unauthorized user, allowing it to be transmitted without unauthorized entities decoding it back into a readable format, thus compromising the data.

Information security uses cryptography on several levels. The information cannot be read without a key to decrypt it. The information maintains its integrity during transit and while being stored. Cryptography also aids in nonrepudiation. This means that the sender and the delivery of a message can be verified.

Cryptography also allows senders and receivers to authenticate each other through the use of key pairs. There are various types of algorithms for encryption, some common algorithms include:

    Secret Key Cryptography (SKC): Here only one key is used for both encryption and decryption. This type of encryption is also referred to as symmetric encryption.
    Public Key Cryptography (PKC): Here two keys are used. This type of encryption is also called asymmetric encryption. One key is the public key that anyone can access. The other key is the private key, and only the owner can access it. The sender encrypts the information using the receiver’s public key. The receiver decrypts the message using his/her private key. For nonrepudiation, the sender encrypts plain text using a private key, while the receiver uses the sender’s public key to decrypt it. Thus, the receiver knows who sent it.
    Hash Functions: These are different from SKC and PKC. They use no key and are also called one-way encryption. Hash functions are mainly used to ensure that a file has remained unchanged.
    
Some encryption methods: 

> Caesar
> Affine Cipher
> Cumulative
> Vigenere
> False Prime Number
> Permutation Technique

----------------------------------------- Türkçe -----------------------------------------

Kriptografi ne anlama geliyor?

Şifreleme, bilgilerin gizli tutulmasına izin veren yazılı veya oluşturulan kodlar oluşturmayı içerir. Şifreleme, verileri yetkisiz bir kullanıcı tarafından okunamayan bir formata dönüştürür, bu sayede yetkisiz kişiler tarafından okunabilir bir formata dönüşmeden aktarılmasına izin verir, böylece verileri tehlikeye atar.

Bilgi güvenliği birkaç seviyede şifreleme kullanır. Bilgi şifresini çözmek için bir anahtar olmadan okunamaz. Bilgi taşıma sırasında ve depolanırken bütünlüğünü korur. Kriptografi ayrıca reddedilmemeye yardımcı olur. Bu, gönderenin ve iletinin tesliminin doğrulanabileceği anlamına gelir. 

Şifreleme ayrıca, gönderenlerin ve alıcıların, anahtar çiftleri kullanarak birbirlerini doğrulamasını sağlar. Şifreleme için çeşitli algoritmalar vardır, bazı yaygın algoritmalar şunları içerir:

    Gizli Anahtar Şifrelemesi (SKC): Burada hem şifreleme hem de şifre çözme için yalnızca bir anahtar kullanılır. Bu şifreleme türü, simetrik şifreleme olarak da adlandırılır.
    Genel Anahtar Şifreleme (PKC): Burada iki anahtar kullanılır. Bu şifreleme türüne asimetrik şifreleme de denir. Bir anahtar, herkesin erişebileceği ortak anahtardır. Diğer anahtar özel anahtardır ve yalnızca sahibi ona erişebilir. Gönderen, alıcının genel anahtarını kullanarak bilgileri şifreler. Alıcı, özel anahtarını kullanarak mesajın şifresini çözer. Reddedilmemesi için gönderen, özel bir anahtar kullanarak düz metni şifreler; alıcı, şifresini çözmek için gönderenin ortak anahtarını kullanır. Böylece alıcı kimin gönderdiğini bilir.
    Karma İşlevleri: Bunlar SKC ve PKC'den farklıdır. Anahtar kullanmazlar ve aynı zamanda tek yönlü şifreleme olarak da adlandırılırlar. Karma işlevleri, bir dosyanın değişmeden kalmasını sağlamak için kullanılır. 
                                                             kaynak: https://www.techopedia.com/definition/1770/cryptography


  Bazı şifreleme yöntemleri:

> Caesar
> Affine Cipher
> Cumulative
> Vigenere
> Yalancı Asal Sayı
> Permütasyon Tekniği
