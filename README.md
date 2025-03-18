# Siber Güvenlik için Makine Öğrenmesi

## Proje Amacı

**Siber Güvenlik için Makine Öğrenmesi** reposu, makine öğrenmesi ve siber güvenlik kesişiminde çalışmalar yapmak isteyen bireyler için kaynaklar ve bilgiler paylaşmayı amaçlamaktadır. Bu projenin ana hedefleri şunlardır:

- Siber güvenlik alanında makine öğrenmesi üzerinde çalışmak isteyenler için kaynaklar sağlamak.
- Bu alanın benzersiz ve spesifik özelliklerini tartışmak.
- Alanda anlayışı ve katılımı artırmak için genel bilgiler sunmak.

## Kullanılabilecek Veri Tipleri

| Veri Türü | Açıklama | Kullanım Alanı |
|-----------|----------|----------------|
| **Ağ Trafiği Verisi** | Ağ üzerinden geçen veri paketleri, IP adresleri, port numaraları ve protokoller içerir. | Anomali tespiti, IDS/IPS, DDoS analizi |
| **Sistem Günlükleri (Logs)** | İşletim sistemleri ve ağ cihazları tarafından üretilen olay kayıtları. | SIEM sistemleri, olay korelasyonu |
| **Kimlik Doğrulama Logları** | Kullanıcı giriş çıkış bilgileri, erişim zamanları. | İç tehdit tespiti, kullanıcı davranış analizi (UBA) |
| **Kötü Amaçlı Yazılım Verileri** | Malware dosyaları, hash değerleri, kod analizleri. | Malware sınıflandırma, antivirüs geliştirme |
| **Alan Adı & IP Verileri** | Şüpheli IP ve alan adları, DNS kayıtları. | Siber tehdit istihbaratı, phishing tespiti |
| **Dosya & Hash Verileri** | Dosya imzaları, MD5/SHA-256 hash değerleri. | İmzaya dayalı tehdit tespiti |
| **Phishing ve E-posta Verileri** | Spam ve phishing e-postaları, şüpheli URL’ler. | Kimlik avı tespiti, e-posta güvenliği |
| **Açık Port ve Servis Verileri** | Açık portlar, kullanılan servisler. | Saldırı yüzeyi analizi, güvenlik açığı değerlendirmesi |
| **Siber Tehdit İstihbaratı** | Güncel tehdit aktörleri, saldırı teknikleri (MITRE ATT&CK). | Proaktif tehdit avı, saldırı tespiti |
| **Güvenlik Açığı Verileri** | CVE kayıtları, exploit verileri. | Zafiyet yönetimi, saldırı tahmini |

## Modeller ve Kullanım Alanları

| Model | Kullanılan Veriler | Kullanım Alanı |
|--------|----------------|-----------------|
| **Anomali Tespiti** | Ağ trafiği, sistem logları | İç tehdit tespiti, ağ güvenliği |
| **Saldırı Tespiti (IDS/IPS)** | Ağ trafiği, açık portlar | Saldırı tespiti ve sınıflandırma |
| **Kötü Amaçlı Yazılım Analizi** | Malware örnekleri, dosya hash verileri | Malware tespiti ve sınıflandırma |
| **Phishing Tespiti** | E-posta, URL verileri | Phishing ve spam filtreleme |
| **UBA & İç Tehdit Analizi** | Kullanıcı davranış verileri, erişim logları | Yetkisiz erişim ve anormal aktivite tespiti |
| **Siber Tehdit İstihbaratı** | IP/domain verileri, tehdit aktörleri | Tehdit avcılığı, saldırı analizi |
| **Açık Port & Güvenlik Açığı Analizi** | Açık portlar, CVE verileri | Penetrasyon testi ve risk analizi |

## Örnek Veri Setleri

| Veri Türü | Örnek Veri Seti |
|-----------|----------------|
| Ağ Trafiği | CICIDS 2017, UNSW-NB15 |
| Sistem Günlükleri | Windows Event Logs, Syslog |
| Kimlik Doğrulama Logları | LDAP, Active Directory Logs |
| Malware Örnekleri | VirusTotal, MalShare, EMBER Dataset |
| IP ve Domain Verileri | AlienVault OTX, Cisco Umbrella |
| Phishing & E-posta | PhishTank, SpamAssassin |
| Açık Port & Servis Verileri | Shodan, Censys |
| Tehdit İstihbaratı | MITRE ATT&CK, MISP Feeds |
| Güvenlik Açığı Verileri | NVD, Exploit-DB |

- (CICIDS 2017)[https://www.unb.ca/cic/datasets/ids-2017.html]
- (UNSW-NB15)[https://research.unsw.edu.au/projects/unsw-nb15-dataset]
- (HIKARI)[https://zenodo.org/records/5199540]
- (ARCS Data Setleri)[https://csr.lanl.gov/data/]




