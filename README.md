Tóm tắt nhanh theo từng tình huống:

**Lần đầu dùng:** đặt `tvn.py` và `install.sh` cùng thư mục → chạy `bash install.sh` → `source ~/.bashrc` → xong, từ đó gõ `tvn` từ bất kỳ đâu.

**Viết và chạy chương trình:**
```bash
# Tạo file .tvn
nano bai.tvn      

# Chạy ngay
tvn bai.tvn

# Biên dịch ra binary
tvn bai.tvn -tf -bai
./bai
```

**Không muốn cài đặt** (chạy thẳng từ folder đã tải về):
```bash
python3 tvn.py bai.tvn
python3 tvn.py bai.tvn -tf -bai
```

**Cần debug** — xem C++ được sinh ra:
```bash
tvn bai.tvn --xem-cpp
```
