
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
**Công nghệ sử dụng:** FastAPI của python.
