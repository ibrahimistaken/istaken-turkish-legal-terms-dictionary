# Rahman ve Rahim Olan Allah'ın Adıyla;

# Turkish Legal Terms Dictionary / Türkçe Hukuki Terimler Sözlüğü

[![Language](https://img.shields.io/badge/language-Turkish-blue.svg)](https://github.com/ibrahimistaken/turkish-legal-terms-dictionary)

---

## 🇹🇷 Türkçe

Bu proje, Türkçe hukuki terimlerin ve anlamlarının bulunduğu kapsamlı bir sözlük içermektedir.

### 📋 İçerik

- **Toplam terim sayısı**: 3.000+ hukuki terim
- **Format**: JSON
- **Dil**: Türkçe
- **Kapsam**: Genel hukuk terimleri, medeni hukuk, ticaret hukuku, ceza hukuku ve diğer hukuk dalları

### 📁 Dosya Yapısı

```
├── turkish-legal-terms-dictionary.json    # Ana sözlük dosyası
└── README.md           # Bu dosya
```

### 🔍 Veri Formatı

Her terim aşağıdaki JSON formatında saklanmaktadır:

```json
{
  "kelime": "Terim",
  "anlam": "Terimin açıklaması"
}
```

### 📖 Örnek Terimler

- **Acenta**: Ticari mümessil, ticari vekil, satış memuru veya müstahdem gibi bir sıfatı olmaksızın bir sözleşmeye dayanarak belirli bir bölge içinde daimi bir suretle ticari bir işletmeyi ilgilendiren akidlerde aracılık etmeyi veya bunları o işletme adına yapmayı meslek edinen kimse
- **Aciz**: Ödeme güçsüzlüğü
- **Açık artırma**: Bir malın, teklif veren kişiler arasında en yüksek bedeli öneren kimseye satılmasını sağlayan satış biçimi
- **Adalet**: Haklılık; hakka uygunluk

### 🚀 Kullanım

Bu sözlük, hukuk öğrencileri, avukatlar, hakimler ve hukuki metinlerle çalışan herkes için faydalı bir kaynak olarak tasarlanmıştır.

#### Programatik Kullanım

```javascript
// JSON dosyasını okuyarak kullanım
const fs = require('fs');
const hukukiSozluk = JSON.parse(fs.readFileSync('turkish-legal-terms-dictionary.json', 'utf8'));

// Belirli bir terimi arama
function terimAra(arananKelime) {
  return hukukiSozluk.find(terim => 
    terim.kelime.toLowerCase().includes(arananKelime.toLowerCase())
  );
}

// Örnek kullanım
const sonuc = terimAra('aciz');
console.log(sonuc);
```

### 📝 Katkıda Bulunma

Bu sözlüğe yeni terimler eklemek veya mevcut terimleri düzeltmek için:

1. `turkish-legal-terms-dictionary.json` dosyasını düzenleyin
2. JSON formatını koruyun
3. Alfabetik sıralamayı göz önünde bulundurun

---

## 🇬🇧 English

This project contains a comprehensive dictionary of Turkish legal terms and their meanings.

### 📋 Content

- **Total number of terms**: 3,000+ legal terms
- **Format**: JSON
- **Language**: Turkish
- **Scope**: General legal terms, civil law, commercial law, criminal law, and other branches of law

### 📁 File Structure

```
├── turkish-legal-terms-dictionary.json    # Main dictionary file
└── README.md           # This file
```

### 🔍 Data Format

Each term is stored in the following JSON format:

```json
{
  "kelime": "Term",
  "anlam": "Term explanation"
}
```

### 📖 Example Terms

- **Acenta**: A person who, without having the status of commercial representative, commercial agent, sales clerk or employee, makes it their profession to mediate in contracts concerning a commercial enterprise within a specific region on a permanent basis, or to perform these on behalf of that enterprise
- **Aciz**: Insolvency; inability to pay
- **Açık artırma**: A sales method that ensures a good is sold to the person offering the highest price among those making offers
- **Adalet**: Justice; conformity to law

### 🚀 Usage

This dictionary is designed as a useful resource for law students, lawyers, judges, and anyone working with legal texts.

#### Programmatic Usage

```javascript
// Reading and using the JSON file
const fs = require('fs');
const legalDictionary = JSON.parse(fs.readFileSync('turkish-legal-terms-dictionary.json', 'utf8'));

// Searching for a specific term
function searchTerm(searchWord) {
  return legalDictionary.find(term => 
    term.kelime.toLowerCase().includes(searchWord.toLowerCase())
  );
}

// Example usage
const result = searchTerm('aciz');
console.log(result);
```

### 📝 Contributing

To add new terms to this dictionary or correct existing terms:

1. Edit the `turkish-legal-terms-dictionary.json` file
2. Maintain the JSON format
3. Consider alphabetical ordering

---

## 📄 License

This project is open source and free for educational use.

## 🔗 Contact

You can use the GitHub Issues section for your questions or suggestions.
