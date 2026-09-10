# ⚠️ Sorumluluk Reddi

## Türkçe

Bu yazılım yalnızca eğitim ve güvenlik araştırması amacıyla geliştirilmiştir. Bu aracı kullanarak doğabilecek her türlü yasal sorumluluğu peşinen kabul etmiş sayılırsınız. Aracın kullanımından doğacak tüm yasal, cezai, idari ve maddi sorumluluk tamamen kullanıcıya aittir. Geliştirici DarkT, bu aracın kötüye kullanımından, üçüncü taraflara verdiği zararlardan, yasadışı amaçlarla kullanılmasından veya kullanıcıların bu araç vasıtasıyla gerçekleştirdiği herhangi bir eylemden dolayı hiçbir şekilde sorumlu tutulamaz. Yazılım "olduğu gibi" sunulmuştur ve hiçbir garanti verilmemektedir. Aracın kullanımı sırasında oluşabilecek veri kaybı, sistem hasarı veya herhangi bir zarardan geliştirici sorumlu değildir. Yasadışı kullanım tespit edilmesi halinde tüm bilgiler yetkili mercilere iletilecek ve yazılım lisansı derhal iptal edilecektir. Bu aracı kullanmadan önce bulunduğunuz ülkenin yasalarını okumanız, yerel yönetmelikleri kontrol etmeniz, hedef numara sahibinden yazılı izin almanız ve gerekirse bir avukata danışmanız gerekmektedir. İzinsiz SMS gönderimi, taciz, tehdit, şantaj, rekabet amaçlı zarar verme ve ticari kazanç sağlama kesinlikle yasaktır. Bu tür eylemler Türk Ceza Kanunu'nun ilgili maddeleri kapsamında 1 yıldan 5 yıla kadar hapis cezası, ağır para cezası, sicil kaydı ve internet erişim yasağı ile sonuçlanabilir. Yasadışı kullanımdan doğacak tüm sonuçlardan münhasıran kullanıcı sorumludur. Bu aracı kullanarak bu şartları okuduğunuzu, anladığınızı ve kabul ettiğinizi beyan etmiş olursunuz.

## English

This software has been developed solely for educational and security research purposes. By using this tool, you are deemed to have accepted in advance all legal responsibilities that may arise. All legal, criminal, administrative, and financial responsibilities arising from the use of this tool belong entirely to the user. The developer DarkT cannot be held responsible in any way for the misuse of this tool, for any damages caused to third parties, for its use for illegal purposes, or for any actions performed by users through this tool. The software is provided "as is" and no warranty of any kind is given. The developer is not responsible for any data loss, system damage, or any other harm that may occur during the use of this tool. In the event that illegal use is detected, all information will be forwarded to the competent authorities and the software license will be immediately revoked. Before using this tool, you must read the laws of your country, check local regulations, obtain written permission from the target number's owner, and consult a lawyer if necessary. Unauthorized SMS sending, harassment, threats, blackmail, causing harm for competitive purposes, and obtaining commercial gain are strictly prohibited. Such actions may result in imprisonment from 1 to 5 years, heavy fines, criminal record, and internet access ban under the relevant articles of the Turkish Penal Code. The user is solely responsible for all consequences arising from illegal use. By using this tool, you declare that you have read, understood, and accepted these terms.



# ⚙️ Parametreler

## Zorunlu Parametreler

| Parametre | Kısa | Uzun | Açıklama | Örnek |
|-----------|------|------|----------|-------|
| Mode | `-m` | `--mode` | Çalışma modu (normal/turbo) | `-m turbo` |

## Hedef Parametreleri

| Parametre | Kısa | Uzun | Açıklama | Örnek |
|-----------|------|------|----------|-------|
| Tek Numara | `-n` | `--number` | Tek telefon numarası | `-n 5413315356` |
| Çoklu Numara | `-N` | `--numbers` | Birden çok numara | `-N 5413315356 5321234567` |
| Dosya | `-f` | `--file` | Numara listesi dosyası | `-f numaralar.txt` |
| Email | `-e` | `--email` | Email adresi (opsiyonel) | `-e mail@example.com` |

## Gönderim Parametreleri

| Parametre | Kısa | Uzun | Açıklama | Varsayılan |
|-----------|------|------|----------|------------|
| Adet | `-c` | `--count` | Gönderilecek SMS sayısı | Sonsuz |
| Aralık | `-i` | `--interval` | İstekler arası süre (saniye) | 1 |

## Tor Parametreleri

| Parametre | Kısa | Uzun | Açıklama | Örnek |
|-----------|------|------|----------|-------|
| Tor | - | `--tor` | Tor üzerinden gönderim | `--tor` |
| Rotate | - | `--rotate` | Her N istekte IP değiştir | `--rotate 3` |
| Check IP | - | `--check-ip` | Mevcut Tor IP'yi göster | `--check-ip` |

## Diğer Parametreler

| Parametre | Kısa | Uzun | Açıklama |
|-----------|------|------|----------|
| List | - | `--list` | Aktif servisleri listele |
| Help | `-h` | `--help` | Yardım menüsünü göster |

## Kullanım Şablonu


bomb -m <mode> [-n <numara>] [-N <numaralar>] [-f <dosya>] [-e <email>] [-c <adet>] [-i <saniye>] [--tor] [--rotate <N>] [--check-ip] [--list] [-h]


