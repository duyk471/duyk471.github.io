# Những nội dung quan trọng nhất mà ta cần học trong Backend

(Lấy từ một chỗ nào đó trên Hacker News rồi dịch lại, không nhớ nguồn T_T)

Có một số khái niệm đáng để tìm hiểu ở mức tổng quan nếu bạn muốn học về việc xây dựng các dự án quy mô lớn. Hầu hết các công ty hiện đại/lớn đều sử dụng một vài hoặc toàn bộ những thành phần sau để xây dựng backend của họ:

* Load balancers (cân bằng tải)
* Web servers (máy chủ web)
* Caches (ví dụ: Redis, memcached)
* Databases (cơ sở dữ liệu: quan hệ, phi quan hệ, tài liệu)
* Search datastores (kho tìm kiếm dữ liệu, ví dụ: Elasticsearch, Solr)
* Log/event/message processors (bộ xử lý log/sự kiện/tin nhắn, ví dụ: Kafka)
* Task queues/task processing libraries (hàng đợi tác vụ/thư viện xử lý tác vụ)
* Periodic jobs (các công việc định kỳ, ví dụ: cron)

Nếu bạn đào sâu vào bất kỳ thành phần nào trong số này, sẽ có rất nhiều điều để học, đặc biệt là khi tìm hiểu về các công nghệ nền tảng được sử dụng để xây dựng những hệ thống cấp cao này.

Ngoài ra còn có những yếu tố mang tính khái niệm hơn, cũng là một phần trong việc xây dựng/duy trì các hệ thống backend. Chúng có phần trừu tượng hơn, nhưng tôi cho rằng cũng quan trọng không kém so với các công nghệ cụ thể:

* Reliability (độ tin cậy)
* Monitoring (giám sát)
* Observability (khả năng quan sát)
* Error/failure handling (xử lý lỗi/sự cố)
* Migration strategies (chiến lược di chuyển dữ liệu/hệ thống)
* Data normalization/denormalization (chuẩn hóa/phi chuẩn hóa dữ liệu)
* Horizontal vs. vertical scalability (khả năng mở rộng ngang so với dọc)

Danh sách này chắc chắn không đầy đủ, nhưng những khái niệm trên là đủ để bạn có định hướng và bắt đầu học tập. Tôi nghĩ **highscalability.com** là một nơi tuyệt vời để đọc về cách các công ty khác đã xây dựng hệ thống backend nhằm giải quyết những vấn đề cụ thể. Trang này có một danh sách khổng lồ các bài viết chất lượng về nhiều hệ thống backend ở quy mô lớn.