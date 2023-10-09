# (Big data application) Sentiment analysis in text documents

- `1-crawl-gplay.ipynb`: crawl data từ Google Play.
- `1-crawl-facebook.ipynb`: crawl data từ Facebook.
- `2-preprocess-eda.ipynb`:  thực hiện preprocess, EDA và label sơ bộ dữ liệu.Dữ liệu sau đó sẽ được nhóm đánh nhãn thủ công.
- `3-modeling.ipynb`: vector hoá bằng TF-IDF, fasttext, PhoBERT và xây dựng mô hình phân lớp.

Ngoài ra còn có 2 thư mục là `data` (chứa `raw` data đã được crawl về, và clean data có được sau khi chạy file `2-preprocess-eda.ipynb`) và `dict` (chứa các file từ điển, teencode, stopword, … để preprocess dữ liệu text).

Để chạy các tập tin đánh số thứ tự 1 và 2, mọi người vui lòng cài các thư viện sau đây:

- scikit-learn.
- google-play-scraper.
- pandas.
- numpy.
- matplotlib.
- seaborn.

Đối với file đánh số thứ tự 3, nhóm khuyến khích chạy trên môi trường Colab hoặc môi trường có thể sử dụng được CUDA vì inference bằng PhoBERT tốn rất nhiều thời gian nếu chạy trên CPU thông thường.
chạy trên CPU thông thường.

Để chạy file `3-modeling.ipynb`, thầy cô vui lòng:

- Mở notebook bằng Colab
- Upload file “data/labeled_data.csv” vào “/content” trên Colab. Nghĩa là ta sẽ có file “/content/labeled_data.csv”.
- Chạy tất cả các cell như bình thường.

Chi tiết các file mã nguồn trong file báo cáo `BigData2 - Project 2.pdf`.

