FileHeaderScanner (Dosya Başlığı Okuyucu)
Amaç:Bu araç, Windows ortamında dosyaların "Magic Bytes" (Dosya İmzası) verilerini okuyarak gerçek dosya türünü analiz eder. Uzantısı değiştirilmiş dosyaları (örneğin .jpg yapılmış bir .exe dosyasını) tespit etmek için kullanılır.

Özellikler:

Dosyanın ilk 2 baytını ASCII, Hex ve Decimal formatlarında gösterir
Dosya türü tahmini (PE, JPEG, PNG, PDF, vb.)
Windows API kullanarak güvenli dosya okuma
Hata yönetimi ve detaylı çıktı
Kullanım:

Scanner.exe <dosya_yolu>
Scanner.exe C:\Windows\notepad.exe
Çıktı Örneği:

=== DOSYA BASLIGI OKUYUCU ===
Dosya: C:\Windows\notepad.exe
Okunan bayt sayisi: 2
Dosyanin ilk iki bayti: MZ
Hex formatinda: 0x4D 0x5A
Decimal formatinda: 77 90
Dosya turu tahmini: PE Executable (.exe, .dll)
