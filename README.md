# 📚 Basic RAG Pipeline with LangChain & HuggingFace

Dự án này minh họa một **pipeline Retrieval-Augmented Generation (RAG) cơ bản** sử dụng **LangChain** và **HuggingFace**.  
Mục tiêu là kết hợp **truy xuất tài liệu** và **mô hình ngôn ngữ lớn (LLM)** để trả lời câu hỏi dựa trên dữ liệu có sẵn.

---

## 🚀 Tổng quan

Pipeline RAG trong notebook bao gồm các bước chính:

- Load dữ liệu văn bản
- Chia nhỏ văn bản (Text Splitting)
- Tạo embedding cho các đoạn văn
- Lưu trữ embedding và truy xuất thông tin liên quan
- Sử dụng LLM để sinh câu trả lời dựa trên context được truy xuất

---

## 🧠 Công nghệ sử dụng

- Python
- LangChain
- HuggingFace Transformers
- Embedding & Vector Search
- Jupyter Notebook

---

## 📁 Cấu trúc dự án

```text
.
├── Basic_Pipeline_RAG.ipynb
└── README.md
```

---

## ⚙️ Cài đặt môi trường

Cài đặt các thư viện cần thiết:

```bash
pip install langchain_core
pip install langchain_community
pip install transformers
```

Khuyến nghị sử dụng **Python 3.9+** và môi trường ảo (venv hoặc conda).

---

## ▶️ Cách sử dụng

### 1. Clone repository

```bash
git clone https://github.com/tutran27/Basiz_RAG_Pipeline
cd your-repo-name
```

### 2. Mở và chạy notebook

```bash
jupyter notebook Basic_Pipeline_RAG.ipynb
```

### 3. Chạy notebook

- Nạp dữ liệu (PDF)
- Tạo embedding
- Truy xuất thông tin
- Đặt câu hỏi và nhận câu trả lời từ LLM

---

## 📌 Mục đích

Dự án này phù hợp cho:

- Người mới tìm hiểu về RAG
- Học và thực hành LangChain
- Xây dựng chatbot hỏi đáp tài liệu
- Nghiên cứu và học tập về LLM

---

## 🔧 Hướng mở rộng

- Thay đổi embedding model
- Sử dụng vector database như FAISS hoặc Chroma
- Tích hợp các LLM khác
- Xây dựng chatbot hoàn chỉnh

---

## 📜 License

Dự án được chia sẻ cho mục đích **học tập, làm quen với RAG**.

---

## ✨ Tác giả

Tu Tran Dinh
