
# Tìm kiếm sách dựa trên nội dung: (sử dụng mô hình Fine-tune vietnamese-sbert)

## Fine-tuning model:
Fine-tune giúp tinh chỉnh mô hình sát với tập dữ liệu đưa vào. Thu hẹp phạm vi để làm giảm chi phí tính toán: thời gian, bộ nhớ...
- Model sau khi sinh ra được lưu vào model-v4
- Tập dữ liệu sinh ra được lưu trong file indexed_book_model_v4.parquet.gzip 

## Data:
- Tập dữ liệu gồm hơn 700 truyện được crawl từ trang https://truyenfull.vn/.
- Các mục crawl: tên truyện, tác giả, tên chương, nội dung, tóm tắt, mở đầu.
- Dữ liệu được làm sạch lưu trong file: cleaned_content.csv
- Dữ liệu trả về front-end: bao gồm link và tên truyện lưu trong file: output.csv
- **Công nghệ sử dụng:** FastAPI của python.
#### Note: Do tập dữ liệu lớn nên được lưu trong đường link: https://husteduvn-my.sharepoint.com/:f:/g/personal/son_kn204602_sis_hust_edu_vn/EkgUBN3lsv1KoIz7H9cHY5wBWNvGrbGdM8t3nmgxpqkJ7A?e=QQHZWS  
- Kiểm tra trên local: truy vấn:" tôi nhớ cô gái ấy", top: 10 =>
![image](https://github.com/sonkn-soict/Book-search-KNS/assets/104115279/270f1c45-f96b-4b9d-813c-930a3b7db4e4)

Kết quả
![image](https://github.com/sonkn-soict/Book-search-KNS/assets/104115279/c3bf4cc8-72d8-4aac-83d8-81f10146e288)
![image](https://github.com/sonkn-soict/Book-search-KNS/assets/104115279/0b163034-1029-4509-96c8-6727e0743414)

