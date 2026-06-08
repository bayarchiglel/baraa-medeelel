# Чиглэл ХХК — Бараа Каталог

GitHub Pages дээр ажилладаг бараа каталог систем.

## 📁 Файлын бүтэц

```
chiglel-catalog/
├── index.html          ← Каталог (хайлт, шүүлт, жагсаалт)
├── product.html        ← Нэг барааны дэлгэрэнгүй хуудас + PDF
├── admin/
│   └── index.html      ← Admin panel (нэвтрэх → засах → хадгалах)
├── data/
│   └── products.json   ← 1031 барааны мэдээлэл
└── README.md
```

## 🚀 Тохируулах заавар

### 1. GitHub Repository үүсгэх
1. github.com → New repository
2. Нэр: `chiglel-catalog`
3. Public сонгох (**GitHub Pages үнэгүй ажиллахад шаардлагатай**)

### 2. Файлуудыг upload хийх
Repository-д эдгээр файлуудыг бүгдийг нь upload хийнэ:
- `index.html`
- `product.html`  
- `admin/index.html`
- `data/products.json`

### 3. GitHub Pages идэвхжүүлэх
1. Repository → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** → **/(root)**
4. Save

Хэдэн минутын дараа: `https://username.github.io/chiglel-catalog`

### 4. Admin Token үүсгэх
1. GitHub → Settings → Developer settings → Personal access tokens
2. **Generate new token (classic)**
3. Note: `Chiglel Admin`
4. Expiration: тохиромжтой хугацаа сонго
5. Scope: ✅ **repo** (бүгд чагтлах)
6. Token-ийг хуулж хадгална — дахин харагдахгүй!

## 📄 PDF Гарын авлага нэмэх заавар

### Google Drive тохируулга
1. Google Drive → Шинэ folder үүсгэх: `Chiglel-Manuals`
2. PDF файлуудыг upload хийх (барааны кодоор нэрлэвэл тохиромжтой)
3. Файл дээр баруун товш → **Share**
4. **"Anyone with the link"** сонгох
5. Линкийг хуулах

### Admin дээр PDF нэмэх
1. `https://username.github.io/chiglel-catalog/admin/` нэвтрэх
2. GitHub repo болон token оруулах
3. Бараа хайж **✏ засах** дарах
4. Google Drive линкийг **"Гарын авлага (PDF)"** талбарт оруулах
5. **Хадгалах** → **Бүгдийг хадгалах**

## 🔍 Сайтын хуудсууд

| Хуудас | URL | Функц |
|--------|-----|-------|
| Каталог | `/index.html` | Хайлт, шүүлт, жагсаалт |
| Бараа | `/product.html?code=953951` | Дэлгэрэнгүй + PDF |
| Admin | `/admin/index.html` | Засах, PDF нэмэх |

## 📊 Мэдээллийн сан

- **1031 бараа** (Sheet2-ээс гаргасан)
- **58 бараа** гарын авлагатай гэж тэмдэглэгдсэн
- Талбарууд: код, нэр, ангилал, үнэ, нөөц, хэмжээ, жин, хүчдэл, хүч, бренд, марк, PDF линк

## ⚠️ Анхаарах зүйлс

- **Token-ийг нуун хадгалах** — бусдад дамжуулж болохгүй
- Token дуусах хугацаандаа шинэчилнэ
- PDF файлууд Google Drive-д "Anyone with the link" тохиргоотой байх ёстой
- GitHub Pages-д deploy болоход 1-2 минут зарцуулдаг

---
*Чиглэл ХХК © 2025 | info@chiglel.mn | +976 7611 5333*
