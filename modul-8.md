Bu repo için acceptance-review isimli bir skill oluştur.

Skill yeni ve izole bir review context'inde çalışsın. Girdi olarak görev kartını,
kabul kriterlerini, git diff'i, değişen testleri ve geliştirici kontrol sonuçlarını alsın.

Her değişen dosyayı bir kabul kriteriyle eşleştirsin. Pozitif, negatif, sınır ve
regresyon senaryoları oluştursun. Beklenen sonucu testi çalıştırmadan önce yazsın.

Yeşil testlerin yanlış beklentiyi veya mevcut kusuru koruyup korumadığını sorgulasın.
README.md, AGENTS.md ve CLAUDE.md içindeki eski veya çelişkili talimatları işaretlesin.

Çıktıyı İddia, Kanıt, Bulgu ve Karar başlıklarıyla hazırlasın.
Karar yalnız Kabul, Düzeltme Gerekli veya Doğrulanamadı olabilir.

Review sırasında kod değiştirmesin, test beklentisini düzeltmesin,
commit veya push yapmasın.

