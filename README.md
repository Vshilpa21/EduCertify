# EduCertify : 🎓 Educhain Certificate Verifier

A sleek and interactive Streamlit web app to verify digital certificates issued by **Educhain**.  
It supports both **JSON file uploads** and **manual form input** to validate credentials based on issuer and signature.

---

## 🚀 Features

- 📤 Upload `.json` certificate files
- ✍️ Enter certificate details manually using a form
- 📜 Live preview of certificate info
- ✅ Real-time verification logic
- 🎨 Beautiful UI with theming and animations

---

## 📁 Certificate JSON Format

```json
{
  "name": "Shilpa Varanasi",
  "course": "AI in Education",
  "issuer": "Educhain",
  "signature": "valid"
}

🧪 Verification Logic
The app checks if:

Issuer is "Educhain"

Signature is "valid"

If both are true, the certificate is marked as verified ✅
Otherwise, it's marked as invalid ❌

🙌 Contributing
Pull requests are welcome! If you want to improve the UI, add blockchain simulation, or enhance logic — feel free to open an issue or PR.

🪪 License
MIT License © 2025 Shilpa Varanasi
