# Custom OpenScope: Nghiên cứu Dữ liệu Không phận Việt Nam

Chào mừng bạn đến với dự án Custom OpenScope. Đây là nghiên cứu cá nhân của tôi nhằm tìm hiểu, xây dựng và tích hợp dữ liệu không phận Việt Nam vào hệ thống mô phỏng không lưu OpenScope. 

Trọng tâm của nghiên cứu này là mô phỏng lại cấu trúc không phận tại khu vực miền Nam, bao gồm Sân bay Quốc tế Tân Sơn Nhất (VVTS) và tính mới ở Sân bay Quốc tế Long Thành (dự kiến).

## 🚀 Hướng dẫn Cài đặt (Set AirportList)

Để tích hợp các sân bay nghiên cứu vào hệ thống, bạn cần thêm đoạn mã sau vào cấu hình `AirportList`:

```json
[
    {
        "icao": "tsn-lt",
        "level": "medium",
        "name": "Tan Son Nhat & Long Thanh",
        "premium": false,
        "disabled": false
    },
    {
        "icao": "vvts",
        "level": "medium",
        "name": "Tan Son Nhat International Airport",
        "premium": false,
        "disabled": false
    }
]

Tham khảo thêm tại: https://www.notion.so/Custom-OpenScope-36473b3467158083b710d832a15c0a49?source=copy_link

