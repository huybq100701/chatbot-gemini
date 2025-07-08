# 🤖 Gemini Multimodal Chatbot - AI Tong hop

Day la ung dung Chatbot da phuong thuc (Multimodal) su dung Gemini API cua Google. Ung dung co cac chuc nang chinh sau:

- 💬 **Chat AI**: Tro chuyen voi AI, ho tro streaming (tra loi dan tung dong).
- 📄 **Tom tat tai lieu**: Ho tro doc va tom tat file `.docx`, `.xlsx`, `.txt`, `pdf`.
- 🖼️ **Mo ta hinh anh**: Phan tich va mo ta noi dung hinh anh.
- 🎨 **Tao/Chinh sua anh bang AI**: Tao anh moi tu prompt hoac chinh sua anh tai len.

---

## 🚀 Huong dan cai dat & chay ung dung
### 0. Thay doi key api (YOUR_API_KEY)

### 1. Tao moi truong ao Python:

(Neu da co, ban co the bo qua buoc nay)

```bash
python -m venv venv
```

### 2. Kich hoat moi truong ao:

**Windows:**

```bash
.\venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 3. Cai dat cac thu vien can thiet:

```bash
pip install -r requirements.txt
```

### 4. Chay ung dung:

```bash
python main.py
```

---

## 🔑 Luu y quan trong:

Ban can cung cap **Gemini API Key** trong file `main.py` de ung dung hoat dong:

```python
GEMINI_API_KEY = "YOUR_GEMINI_API_KEY"
```

> Co the lay API Key tai: [https://aistudio.google.com/u/1/apikey?hl=vi](https://aistudio.google.com/u/1/apikey?hl=vi)

---

## 📦 Cau truc file trong du an:

```
.
├── main.py               # File code chinh
├── requirements.txt      # Danh sach thu vien can cai
└── README.md             # Huong dan (file nay)
```

---

## 💡 Mot so tinh nang noi bat:

- Toan bo giao dien tieng Viet, de su dung.
- Ho tro streaming cho chuc nang Chat AI (hien thi dan tung dong).
- Cac tab rieng biet cho tung chuc nang.
- Co nut 🗑️ de xoa nhanh lich su chat o moi tab.
- Giao dien ro rang, truc quan, de mo rong.

---

## 📝 Thong tin them:

- Ung dung chi chay cuc bo tren may, **khong luu tru du lieu nguoi dung**.
- Ho tro tot cho nguoi dung Viet Nam.

---

## ✅ Ban quyen:

Ung dung chi mang tinh **hoc tap, thu nghiem** voi Gemini API.
