# Smart Washing / Dryer Monitor Blueprint

Blueprint Home Assistant để giám sát:
- 🧺 Máy giặt
- 🔥 Máy sấy
- 🍽 Máy rửa bát

## Tính năng
- ✅ Phát hiện chạy xong (không báo sai khi standby)
- ❌ Phát hiện dừng sớm / lỗi
- ⚠️ Phát hiện quá tải / kẹt
- ⏱ Kiểm tra thời gian chạy tối thiểu
- 🔁 Tự reset lỗi khi chạy lại
- 🌐 Chạy 100% local – không cloud

---

## Yêu cầu
- Home Assistant 2023.5+
- Có sensor công suất (W)

---

## Cài đặt (2 cách)

### Cách 1 – Import bằng link (Khuyên dùng)
1. Vào Home Assistant  
2. Cài đặt → Tự động hóa → Blueprints  
3. Chọn **Import Blueprint**
4. Dán link:
   - **Smart Washing / Dryer Monitor**: https://raw.githubusercontent.com/hoducnguyenhd/ha-blueprints/main/blueprints/automation/smart_washer_dryer_monitor.yaml
   - **siren_play**:  https://raw.githubusercontent.com/hoducnguyenhd/ha-blueprints/main/blueprints/automation/siren_play.yaml
   - **RFID-Tag-name**:  https://raw.githubusercontent.com/hoducnguyenhd/ha-blueprints/main/blueprints/automation/RFID-TAG-NAME.yaml
