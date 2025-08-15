MATLAB–Simulink Deneylerim (Denetim Sistemleri)


Bu depo, Denetim Sistemleri laboratuvarında gerçekleştirdiğim MATLAB–Simulink deneylerini içerir. Amaç; temel kontrol kuramı kavramlarını hem analitik (MATLAB) hem de simülasyon (Simulink) ortamında uygulamak, sonuçları karşılaştırmak ve raporlamaktır.

Bu çalışma, kök yer eğrisi, kararlılık analizi (Routh–Hurwitz), ikinci dereceden sistemlerin zaman cevabı, frekans cevabı (Bode/Nyquist), PID tasarımı ve (varsa) durum-uzayı temelli kontrol başlıklarını kapsar.

Kontrol sistemleri laboratuvarı kapsamında MATLAB–Simulink ile kök yer eğrisi, Routh–Hurwitz, zaman/frekans cevabı ve PID tasarımı üzerine deneyler yaptım. İkinci derece sistem parametrelerini değiştirerek %OS, Tp, Ts metriklerini analiz ettim; frekans alanında Bode grafikleriyle faz/kazanç payı ve bant genişliği ilişkisini inceledim. Simulink modelleri geliştirip parametrik çalışma yaptım, bulguları tablolar ve grafiklerle raporladım.

📁 Klasör Yapısı

Klasör adları depo görünümündeki düzene göre verilmiştir (deney1–deney6). İçeriğin tam adı/konusu klasör içeriğine göre güncellenebilir. 
GitHub

.
├─ deney1/   # Kök Yer Eğrisi (Root Locus) – kutup/sıfır etkisi, K değişimi

├─ deney2/   # Routh–Hurwitz kararlılık testi – işaret değişimleri, kararlılık şartı

├─ deney3/   # İkinci derece sistem – adım cevabı: ζ, ωn, %OS, Ts, Tp

├─ deney4/   # Frekans cevabı – Bode genlik/faz, bant genişliği, kararlılık payları

├─ deney5/   # PID kontrolör – P/PI/PID ayarı, yükselme/yerleşme süreleri

└─ deney6/   # (Varsa) Durum geribesleme / Gözleyici / Kutup yerleştirme


🧭 İçerik ve Öğrenme Hedefleri

Kök Yer Eğrisi (deney1): Kazanç (K) değişiminin kapalı çevrim kutuplarına etkisini inceleme; performans–kararlılık dengesi.

Routh–Hurwitz (deney2): Karakteristik polinomdan kararlılık kontrolü; sınır-kararlı durumların yorumlanması.

Zaman Domeni Analizi (deney3): ζ, ωn, %OS, Tp, Ts gibi metriklerin deneysel ölçümü ve hedefe göre ayarlama.

Frekans Domeni (deney4): Bode genlik/faz grafikleri; faz/gevşeklik payları, bant genişliği ve kararlılıkla ilişkisi.

PID Tasarımı (deney5): P, PI, PID karşılaştırması; aşım–yerleşme–hata dengesi; ayar yöntemlerinin kıyası.

Durum-Uzayı (deney6): (Varsa) Kutup yerleştirme, Luenberger/Kalman gözleyiciye giriş.


🧰 Gereksinimler

## MATLAB (R2020b veya üstü önerilir)

## Control System Toolbox

## Simulink


📊 Kazanımlar

- MATLAB/Simulink ile modelleme ve simülasyon  
- Kök yer eğrisi, Routh–Hurwitz, Bode/Nyquist, PID pratiği  
- Zaman & frekans domeni performans analizi  
- Teknik raporlama ve sonuç sunumu


👤 İletişim Bilgilerim : 

- e-posta: yusufefekochan@hotmail.com
  
- LinkedIn: https://www.linkedin.com/in/yusufefekochan



