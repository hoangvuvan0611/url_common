# The Execution Lifecycle of a Java Application
[Article ](https://www.cesarsotovalero.net/blog/how-the-jvm-executes-java-code.html#execution-lifecycle)

Nếu bạn đang đọc bài viết này, nhiều khả năng bạn đã biết cách viết code Java. Điều đó thật tuyệt vời, 
tôi cho rằng trong thời đại ngày nay mọi người đều nên biết lập trình (giống như việc tất cả chúng ta 
đều cần hiểu các phép toán cơ bản như cộng, trừ, nhân, chia dù ai cũng có máy tính). Trong một bài viết 
trước, tôi đã đề cập đến việc code Java đầu tiên được "biên dịch" thành bytecode và sau đó được thông 
dịch và thực thi bởi JVM. Tuy nhiên, tôi chưa giải thích cách JVM thực sự thực thi bytecode. Mục đích 
của bài viết này chính là lấp đầy khoảng trống đó. Tôi sẽ trả lời câu hỏi: Điều gì xảy ra khi bạn nhấn 
nút "execute" trên IDE yêu thích của mình? Sau khi đọc bài viết này, bạn sẽ hiểu được vòng đời thực thi 
của một ứng dụng Java và các hoạt động được JVM thực hiện trong giai đoạn thực thi.


