# NGÂN HÀNG CÂU HỎI ÔN TẬP PRM393 — 116 CÂU DUY NHẤT (ĐÃ LỌC TRÙNG)

Tài liệu được tổng hợp và loại bỏ hoàn toàn các câu trùng lặp từ 5 bộ đề ôn tập môn **PRM393** trên FTES.
- **Tổng số câu gốc (5 đề):** 250 câu
- **Số câu thực tế sau khi lọc trùng:** 116 câu
- **Đáp án chuẩn:** FrosTES

---
**Câu 1. What is the purpose of JWT?**  
- A. Encrypt UI  
- **B. Represent user session**  
- C. Store images  
- D. Manage navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** JWT (JSON Web Token) là cơ chế mã hóa stateless dùng để đại diện và duy trì phiên làm việc của người dùng (user session). Khi đăng nhập thành công, server trả về JWT để client gửi kèm trong mỗi request xác thực tiếp theo.


**Câu 2. What type of data is SharedPreferences best suited for?**  
- A. Large datasets  
- **B. Simple primitive values**  
- C. Images  
- D. Complex objects  
*-> Đáp án: B*
> 💡 **Giải thích:** SharedPreferences dùng để lưu trữ các cặp key-value dữ liệu nguyên thủy (primitive values như int, double, bool, String). Không phù hợp cho tập dữ liệu lớn hay quan hệ phức tạp (vốn cần dùng SQLite/Drift).


**Câu 3. Which concept helps test business logic easily?**  
- A. UI testing  
- **B. Separation of logic**  
- C. Hot reload  
- D. Layouts  
*-> Đáp án: B*
> 💡 **Giải thích:** Tách biệt logic nghiệp vụ khỏi UI (Separation of logic) giúp viết Unit Test cho logic dễ dàng, độc lập mà không cần phải mount widget tree hay giả lập giao diện người dùng.


**Câu 4. Which pattern separates storage logic from UI?**  
- A. MVC  
- **B. Repository pattern**  
- C. Singleton  
- D. Factory  
*-> Đáp án: B*
> 💡 **Giải thích:** Repository Pattern đóng vai trò làm trung gian phân tách logic lưu trữ/truy xuất dữ liệu (Storage/API) khỏi tầng UI/BLoC, giúp UI không cần biết dữ liệu đến từ đâu (Local DB hay Remote API).


**Câu 5. What is the purpose of building a release version of a Flutter app?**  
- A. Debug code  
- **B. Prepare app for distribution**  
- C. Test UI  
- D. Change theme  
*-> Đáp án: B*
> 💡 **Giải thích:** Bản build Release biên dịch code sang dạng mã máy tối ưu (AOT compilation, tree-shaking, loại bỏ debug banner và code kiểm thử) nhằm chuẩn bị phân phối ứng dụng cho người dùng cuối trên App Store / CH Play.


**Câu 6. Why is logout functionality important?**  
- A. Free memory  
- **B. End user session securely**  
- C. Improve UI  
- D. Change theme  
*-> Đáp án: B*
> 💡 **Giải thích:** Chức năng đăng xuất (logout) rất quan trọng để kết thúc an toàn phiên làm việc của người dùng (End user session securely), xóa sạch access token/JWT khỏi bộ nhớ thiết bị để ngăn truy cập trái phép.


**Câu 7. Which widget is an example of implicit animation?**  
- **A. AnimatedContainer**  
- B. AnimationController  
- C. Tween  
- D. Ticker  
*-> Đáp án: A*
> 💡 **Giải thích:** AnimatedContainer là widget hoạt ảnh ngầm định (Implicit Animation). Bạn chỉ cần thay đổi các thuộc tính như width, height, color thì Flutter sẽ tự động animate mượt mà giữa giá trị cũ và mới mà không cần AnimationController.


**Câu 8. Which scenario best fits local state management?**  
- A. User authentication  
- B. Theme selection  
- **C. TextField input**  
- D. API token storage  
*-> Đáp án: C*
> 💡 **Giải thích:** Nội dung người dùng đang gõ vào TextField (TextField input) chỉ có phạm vi cục bộ trên màn hình/widget đó, do đó quản lý bằng Local State (setState/TextEditingController) là phù hợp và tối ưu nhất.


**Câu 9. Which programming language is used to develop Flutter applications?**  
- A. Kotlin  
- B. Swift  
- **C. Dart**  
- D. JavaScript  
*-> Đáp án: C*
> 💡 **Giải thích:** Dart là ngôn ngữ lập trình hướng đối tượng do Google phát triển, được sử dụng làm ngôn ngữ chính để phát triển toàn bộ ứng dụng và framework Flutter.


**Câu 10. Why is the widget tree considered immutable?**  
- A. Widgets cannot be removed  
- **B. Widgets are recreated instead of modified**  
- C. Widgets are stored permanently  
- D. Widgets cannot contain data  
*-> Đáp án: B*
> 💡 **Giải thích:** Trong Flutter, Widget Tree là bất biến (immutable). Khi trạng thái thay đổi, widget cũ không bị sửa mà sẽ được tạo lại (recreated). Flutter sau đó sẽ so sánh với Element Tree để chỉ cập nhật những phần cần thiết trên màn hình.


**Câu 11. Which widget is suitable for displaying items in a grid layout?**  
- A. ListView  
- B. Column  
- **C. GridView**  
- D. Stack  
*-> Đáp án: C*
> 💡 **Giải thích:** GridView là widget chuyên dụng để hiển thị danh sách các phần tử theo dạng lưới 2 chiều (hàng và cột).


**Câu 12. What causes unnecessary widget rebuilds?**  
- A. State changes  
- **B. Overusing setState()**  
- C. Using Provider  
- D. Using const widgets  
*-> Đáp án: B*
> 💡 **Giải thích:** Lạm dụng setState() ở các widget cha cấp cao sẽ khiến toàn bộ cây widget con bên dưới bị rebuild lại không cần thiết, làm giảm hiệu năng khung hình (FPS) của ứng dụng.


**Câu 13. Which feature of Dart helps prevent null reference errors at compile time?**  
- A. Dynamic typing  
- B. Hot reload  
- **C. Null safety**  
- D. Asynchronous execution  
*-> Đáp án: C*
> 💡 **Giải thích:** Null Safety trong Dart giúp phát hiện và ngăn chặn các lỗi truy cập null (Null pointer exceptions) ngay tại thời điểm biên dịch (Compile time) thay vì xảy ra crash lúc chạy ứng dụng (Runtime).


**Câu 14. When should you prefer Provider over setState()?**  
- A. For simple UI updates  
- **B. For global or shared state**  
- C. For animations  
- D. For navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Nên dùng Provider (hoặc BLoC/Riverpod) khi cần quản lý và chia sẻ trạng thái dùng chung (global / shared state) giữa nhiều widget hoặc nhiều màn hình khác nhau.


**Câu 15. Which practice reduces technical debt?**  
- A. Quick fixes  
- **B. Consistent refactoring**  
- C. Ignoring tests  
- D. Skipping reviews  
*-> Đáp án: B*
> 💡 **Giải thích:** Tái cấu trúc mã nguồn liên tục và nhất quán (Consistent refactoring) giúp mã sạch, dễ bảo trì, loại bỏ code thừa và giảm thiểu nợ kỹ thuật (Technical debt) trong dự án dài hạn.


**Câu 16. What is authentication primarily used for?**  
- A. Data storage  
- **B. User identity verification**  
- C. UI rendering  
- D. Navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Xác thực (Authentication) chủ yếu dùng để kiểm tra và xác minh danh tính người dùng (User identity verification), đảm bảo người dùng đúng là chủ sở hữu tài khoản.


**Câu 17. Why are different build flavors useful?**  
- A. UI themes  
- **B. Multiple app configurations**  
- C. Faster rendering  
- D. Simpler navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Build Flavors (trên Android/iOS) cho phép tạo nhiều cấu hình ứng dụng khác nhau từ cùng một codebase (ví dụ: môi trường Dev, Staging, Production với API URL và icon khác nhau).


**Câu 18. What advantage does a single codebase provide in Flutter development?**  
- A. Higher memory usage  
- B. Simpler UI customization  
- **C. Reduced development and maintenance effort**  
- D. Automatic database synchronization  
*-> Đáp án: C*
> 💡 **Giải thích:** Một trong những ưu điểm lớn nhất của Flutter là Single Codebase: viết code 1 lần nhưng biên dịch và chạy trên nhiều nền tảng, giúp giảm thiểu đáng kể chi phí phát triển và bảo trì.


**Câu 19. What is the primary role of widgets in Flutter?**  
- A. Managing databases  
- **B. Describing the user interface**  
- C. Handling network requests  
- D. Compiling Dart code  
*-> Đáp án: B*
> 💡 **Giải thích:** Trong Flutter, 'Everything is a widget'. Widget là các khối cấu trúc cơ bản dùng để mô tả giao diện người dùng (Describing the user interface) tại từng thời điểm.


**Câu 20. Why is user feedback valuable?**  
- A. Delay project  
- **B. Improve product usability**  
- C. Change architecture  
- D. Reduce scope  
*-> Đáp án: B*
> 💡 **Giải thích:** Phản hồi của người dùng (User feedback) giúp nhà phát triển nhận diện các điểm bất tiện, tối ưu trải nghiệm người dùng và cải thiện tính dễ sử dụng (Product usability) của ứng dụng.


**Câu 21. What problem does state hoisting address?**  
- A. API delay  
- **B. State duplication**  
- C. Theme conflict  
- D. Navigation error  
*-> Đáp án: B*
> 💡 **Giải thích:** State Hoisting (nâng trạng thái lên widget cha) giúp tránh việc sao chép/đồng bộ dữ liệu phân tán (State duplication), biến widget con thành stateless dễ tái sử dụng.


**Câu 22. What happens when setState() is called in a StatefulWidget?**  
- A. The app restarts  
- **B. The widget tree is rebuilt**  
- C. Data is saved permanently  
- D. Navigation occurs  
*-> Đáp án: B*
> 💡 **Giải thích:** Khi gọi setState(), Flutter sẽ đánh dấu State object đó là 'dirty' và lên lịch chạy lại phương thức build(), dẫn đến Widget Tree tương ứng được xây dựng lại (rebuilt).


**Câu 23. Which pattern is commonly used for scalable state management?**  
- A. MVC  
- **B. BLoC**  
- C. Singleton  
- D. Factory  
*-> Đáp án: B*
> 💡 **Giải thích:** BLoC (Business Logic Component) là kiến trúc quản lý trạng thái có khả năng mở rộng cao (Scalable), sử dụng Streams để tách biệt hoàn toàn Business Logic ra khỏi giao diện UI.


**Câu 24. Which input type improves user experience for emails?**  
- A. TextInputType.number  
- **B. TextInputType.emailAddress**  
- C. TextInputType.text  
- D. TextInputType.url  
*-> Đáp án: B*
> 💡 **Giải thích:** Thuộc tính TextInputType.emailAddress sẽ tự động hiển thị bàn phím ảo có sẵn phím '@' và tên miền, giúp trải nghiệm nhập email của người dùng thuận tiện và ít sai sót hơn.


**Câu 25. Which sliver is commonly used to display a scrolling list?**  
- A. SliverGrid  
- **B. SliverList**  
- C. SliverAppBar  
- D. SliverFillRemaining  
*-> Đáp án: B*
> 💡 **Giải thích:** SliverList là một thành phần sliver bên trong CustomScrollView chuyên dùng để hiển thị danh sách cuộn mượt mà cùng với các sliver khác như SliverAppBar.


**Câu 26. Which method validates all form fields?**  
- **A. validate()**  
- B. check()  
- C. verify()  
- D. submit()  
*-> Đáp án: A*
> 💡 **Giải thích:** Phương thức FormState.validate() duyệt qua tất cả các FormField con và gọi hàm validator() của từng trường để kiểm tra tính hợp lệ của toàn bộ biểu mẫu.


**Câu 27. Which HTTP method is used to send new data to a server?**  
- A. GET  
- B. DELETE  
- **C. POST**  
- D. HEAD  
*-> Đáp án: C*
> 💡 **Giải thích:** Phương thức HTTP POST được quy định dùng để gửi dữ liệu mới lên máy chủ (thường là tạo mới bản ghi trong RESTful API).


**Câu 28. What is the main goal of performance optimization in Flutter apps?**  
- A. Improve UI colors  
- **B. Ensure smooth and responsive UI**  
- C. Reduce code size  
- D. Add features  
*-> Đáp án: B*
> 💡 **Giải thích:** Mục tiêu chính của tối ưu hiệu năng trong Flutter là đảm bảo giao diện luôn mượt mà (đạt 60fps hoặc 120fps) và phản hồi tức thì với các thao tác vuốt chạm của người dùng.


**Câu 29. What is dependency injection used for?**  
- A. UI updates  
- **B. Manage object dependencies**  
- C. Theme control  
- D. Navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Dependency Injection (DI) là kỹ thuật cung cấp các đối tượng phụ thuộc từ bên ngoài vào thay vì khởi tạo cứng bên trong class, giúp quản lý phụ thuộc linh hoạt và dễ mock khi viết test.


**Câu 30. Which layer should handle authentication logic?**  
- A. UI layer  
- B. Data layer  
- **C. Service layer**  
- D. Theme layer  
*-> Đáp án: C*
> 💡 **Giải thích:** Logic xác thực người dùng (gọi API login, lưu token, kiểm tra quyền) thuộc về tầng dịch vụ (Service layer / AuthenticationService), không nên viết trực tiếp trong tầng UI.


**Câu 31. What does the final keyword indicate in Dart?**  
- A. The variable can be reassigned later  
- **B. The variable value is fixed after assignment**  
- C. The variable is global  
- D. The variable is private  
*-> Đáp án: B*
> 💡 **Giải thích:** Từ khóa 'final' trong Dart quy định rằng biến chỉ có thể được gán giá trị một lần duy nhất, sau khi đã gán thì không thể thay đổi giá trị được nữa.


**Câu 32. Which status code indicates resource not found?**  
- A. 200  
- B. 301  
- **C. 404**  
- D. 500  
*-> Đáp án: C*
> 💡 **Giải thích:** Mã trạng thái HTTP 404 (Not Found) biểu thị rằng tài nguyên được yêu cầu không tồn tại trên máy chủ.


**Câu 33. What represents the output of a BLoC?**  
- A. Events  
- B. Widgets  
- **C. States**  
- D. Controllers  
*-> Đáp án: C*
> 💡 **Giải thích:** Trong kiến trúc BLoC, đầu vào là các Sự kiện (Events) và đầu ra từ BLoC phát ra là các Trạng thái (States) thông qua Stream.


**Câu 34. Which widget arranges its children horizontally?**  
- A. Column  
- B. Stack  
- **C. Row**  
- D. Align  
*-> Đáp án: C*
> 💡 **Giải thích:** Widget Row sắp xếp các widget con của nó theo chiều ngang (horizontal), trong khi Column sắp xếp theo chiều dọc (vertical).


**Câu 35. What is the role of vsync?**  
- A. Sync data  
- **B. Optimize animation resources**  
- C. Control layout  
- D. Handle navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** vsync (TickerProvider) đồng bộ hóa vòng lặp hoạt ảnh với tốc độ làm tươi màn hình của thiết bị, giúp tối ưu hóa tài nguyên và ngăn hoạt ảnh chạy lãng phí khi màn hình bị ẩn.


**Câu 36. Which test runs fastest?**  
- A. Integration test  
- B. Widget test  
- **C. Unit test**  
- D. Manual test  
*-> Đáp án: C*
> 💡 **Giải thích:** Unit test kiểm tra các hàm/class logic độc lập không cần render UI, do đó tốc độ thực thi của nó là nhanh nhất (thường tính bằng mili-giây).


**Câu 37. Why is understanding the widget lifecycle important?**  
- A. Improve API performance  
- **B. Manage UI updates correctly**  
- C. Deploy apps faster  
- D. Reduce file size  
*-> Đáp án: B*
> 💡 **Giải thích:** Hiểu rõ vòng đời widget (initState, didUpdateWidget, dispose...) giúp nhà phát triển khởi tạo tài nguyên, lắng nghe luồng dữ liệu và giải phóng bộ nhớ đúng cách.


**Câu 38. Why are real-world requirements important?**  
- A. Increase complexity  
- **B. Reflect actual user needs**  
- C. Change theme  
- D. Slow development  
*-> Đáp án: B*
> 💡 **Giải thích:** Yêu cầu thực tế (Real-world requirements) phản ánh đúng nhu cầu và hành vi của người dùng thật, giúp sản phẩm xây dựng ra giải quyết đúng vấn đề và có giá trị sử dụng cao.


**Câu 39. Which protocol is commonly used for secure authentication?**  
- A. HTTP  
- B. FTP  
- **C. OAuth 2.0**  
- D. SMTP  
*-> Đáp án: C*
> 💡 **Giải thích:** OAuth 2.0 là giao thức chuẩn công nghiệp được sử dụng phổ biến nhất hiện nay cho việc ủy quyền và xác thực an toàn (ví dụ: Đăng nhập bằng Google, Facebook, GitHub).


**Câu 40. What design principle improves form usability?**  
- A. Long forms  
- B. Minimal validation  
- **C. Clear labels and feedback**  
- D. Hidden errors  
*-> Đáp án: C*
> 💡 **Giải thích:** Thiết kế biểu mẫu tốt cần có nhãn rõ ràng (Clear labels) và thông báo phản hồi lỗi tức thì (Feedback) khi người dùng nhập sai để nâng cao tính khả dụng (Usability).


**Câu 41. Which database is commonly used for structured local data?**  
- A. Firebase  
- **B. SQLite**  
- C. MongoDB  
- D. MySQL  
*-> Đáp án: B*
> 💡 **Giải thích:** SQLite là cơ sở dữ liệu quan hệ (Relational DB) nhúng cục bộ được sử dụng phổ biến nhất trên thiết bị di động để lưu trữ dữ liệu có cấu trúc dạng bảng.


**Câu 42. Why is Chapter 5 often considered optional or plus content?**  
- A. It replaces layout widgets  
- **B. Themes are not required for functionality**  
- C. It manages navigation  
- D. It handles state  
*-> Đáp án: B*
> 💡 **Giải thích:** Theme (chủ đề màu sắc/giao diện) giúp ứng dụng đẹp hơn nhưng không ảnh hưởng tới logic vận hành cốt lõi của tính năng, vì vậy thường được xếp vào nội dung bổ trợ (plus content).


**Câu 43. What format is most commonly used in REST APIs?**  
- A. XML  
- B. CSV  
- **C. JSON**  
- D. Binary  
*-> Đáp án: C*
> 💡 **Giải thích:** JSON (JavaScript Object Notation) là định dạng trao đổi dữ liệu nhẹ, dạng text, dễ đọc hiểu và được sử dụng rộng rãi nhất trong các dịch vụ RESTful API.


**Câu 44. Why is passing context important in navigation?**  
- A. Access theme  
- **B. Access Navigator**  
- C. Access state  
- D. Access layout  
*-> Đáp án: B*
> 💡 **Giải thích:** BuildContext cho biết vị trí của widget trong widget tree, điều này bắt buộc để Navigator tìm thấy NavigatorState cấp gần nhất nhằm thực hiện chuyển trang.


**Câu 45. Which component is responsible for rendering UI in Flutter?**  
- A. Native UI components  
- **B. The Flutter engine**  
- C. The operating system  
- D. The backend server  
*-> Đáp án: B*
> 💡 **Giải thích:** Flutter Engine (viết bằng C++) chịu trách nhiệm rasterize các lệnh đồ họa (sử dụng Skia/Impeller) và render trực tiếp các điểm ảnh lên màn hình thiết bị.


**Câu 46. Which Dart feature allows defining reusable, type-safe components?**  
- A. Mixins  
- **B. Generics**  
- C. Futures  
- D. Streams  
*-> Đáp án: B*
> 💡 **Giải thích:** Generics trong Dart (ví dụ: List<T>, Stream<T>) cho phép định nghĩa các component có thể tái sử dụng cho nhiều kiểu dữ liệu khác nhau mà vẫn đảm bảo Type-safe tại thời điểm biên dịch.


**Câu 47. Which Flutter service simplifies authentication implementation?**  
- A. sqflite  
- **B. Firebase Authentication**  
- C. Provider  
- D. http  
*-> Đáp án: B*
> 💡 **Giải thích:** Firebase Authentication cung cấp sẵn SDK toàn diện hỗ trợ xác thực qua Email/Password, Google, Apple, Phone... giúp đơn giản hóa việc triển khai đăng nhập an toàn.


**Câu 48. Which widget rebuilds automatically during animation?**  
- **A. AnimatedBuilder**  
- B. FutureBuilder  
- C. StreamBuilder  
- D. LayoutBuilder  
*-> Đáp án: A*
> 💡 **Giải thích:** AnimatedBuilder lắng nghe sự thay đổi từ Listenable (như AnimationController) và tự động gọi lại hàm builder() để vẽ lại widget khi hoạt ảnh chạy.


**Câu 49. What does the Padding widget do?**  
- **A. Adds space inside a widget**  
- B. Adds space between widgets  
- C. Aligns widgets  
- D. Controls widget size  
*-> Đáp án: A*
> 💡 **Giải thích:** Widget Padding dùng để tạo khoảng đệm (trống) bên trong viền của widget đối với nội dung con của nó.


**Câu 50. What is the purpose of the Flutter SDK?**  
- A. To store application data permanently  
- **B. To provide tools and libraries for Flutter development**  
- C. To deploy applications directly to app stores  
- D. To replace the operating system of a device  
*-> Đáp án: B*


---
> 💡 **Giải thích:** Flutter SDK cung cấp đầy đủ công cụ CLI (flutter build, flutter run), engine, compiler và các thư viện widget phong phú phục vụ toàn diện việc phát triển ứng dụng.


**Câu 51. Which Flutter widget reacts to authentication state changes?**  
- A. FutureBuilder  
- **B. StreamBuilder**  
- C. ListView  
- D. Form  
*-> Đáp án: B*
> 💡 **Giải thích:** StreamBuilder lắng nghe luồng Stream dữ liệu trạng thái (ví dụ FirebaseAuth.instance.authStateChanges()) và tự động rebuild UI tương ứng khi người dùng login hoặc logout.


**Câu 52. Why is separating UI and state logic recommended?**  
- A. Reduce code size  
- **B. Improve maintainability**  
- C. Faster execution  
- D. Better animations  
*-> Đáp án: B*
> 💡 **Giải thích:** Tách biệt UI và logic trạng thái giúp code sạch, dễ đọc, dễ bảo trì (Improve maintainability) và cho phép các lập trình viên làm việc song song hiệu quả.


**Câu 53. What does crossAxisAlignment control?**  
- A. Vertical alignment in Column  
- **B. Horizontal alignment in Column**  
- C. Child order  
- D. Widget size  
*-> Đáp án: B*
> 💡 **Giải thích:** Trong Column, crossAxisAlignment điều khiển việc căn chỉnh các phần tử con theo trục phụ (trục ngang - horizontal alignment).


**Câu 54. What happens after successful login?**  
- A. App closes  
- **B. User session starts**  
- C. Theme changes  
- D. Navigation resets  
*-> Đáp án: B*
> 💡 **Giải thích:** Sau khi đăng nhập thành công, phiên làm việc của người dùng chính thức bắt đầu (User session starts), ứng dụng sẽ lưu token và điều hướng vào trang chính (Home).


**Câu 55. What is Dart primarily designed for in the Flutter ecosystem?**  
- A. Database management  
- B. User interface development  
- **C. General-purpose programming with UI focus**  
- D. Network security  
*-> Đáp án: C*
> 💡 **Giải thích:** Dart được Google thiết kế tối ưu hóa đặc biệt cho việc phát triển giao diện người dùng (UI development), hỗ trợ cả JIT (cho Hot Reload) và AOT (cho bản Release nhanh).


**Câu 56. What does the build() method return in a widget?**  
- A. A screen  
- **B. A widget tree describing the UI**  
- C. Application state  
- D. Rendered pixels  
*-> Đáp án: B*
> 💡 **Giải thích:** Phương thức build() trả về một Widget Tree (cây widget) mô tả cách giao diện người dùng được hiển thị dựa trên trạng thái hiện tại.


**Câu 57. What is the main goal of testing in Flutter apps?**  
- A. Improve UI design  
- **B. Ensure app quality and correctness**  
- C. Speed up builds  
- D. Manage state  
*-> Đáp án: B*
> 💡 **Giải thích:** Mục tiêu cốt lõi của việc viết test trong Flutter là đảm bảo chất lượng, tính đúng đắn của logic (Ensure app quality and correctness) và ngăn chặn lỗi hồi quy (regression).


**Câu 58. Which Dart feature supports object-oriented programming?**  
- A. Widgets  
- **B. Classes and objects**  
- C. Hot reload  
- D. Layout builders  
*-> Đáp án: B*
> 💡 **Giải thích:** Dart là ngôn ngữ thuần hướng đối tượng (Pure OOP), hỗ trợ đầy đủ các khái niệm Lớp và Đối tượng (Classes and Objects), Kế thừa, Đa hình và Đóng gói.


**Câu 59. When is it most appropriate to customize themes in a Flutter app?**  
- A. After API integration  
- **B. During UI/UX design phase**  
- C. Only at deployment  
- D. Only for testing  
*-> Đáp án: B*
> 💡 **Giải thích:** Tùy biến Theme (ThemeData, ColorScheme) nên được thực hiện trong giai đoạn thiết kế UI/UX để đảm bảo tính nhất quán về màu sắc, font chữ trên toàn bộ ứng dụng.


**Câu 60. Why should architecture be decided early?**  
- A. Avoid UI work  
- **B. Reduce refactoring cost**  
- C. Improve animations  
- D. Change theme  
*-> Đáp án: B*
> 💡 **Giải thích:** Quyết định kiến trúc ứng dụng (BLoC, MVVM, Clean Architecture) ngay từ đầu giúp giảm thiểu chi phí và công sức đập đi viết lại (Refactoring cost) khi dự án lớn lên.


**Câu 61. Which step is required before running a Flutter app for the first time?**  
- A. Publishing the app  
- **B. Setting up the Flutter SDK**  
- C. Configuring a database  
- D. Writing backend APIs  
*-> Đáp án: B*
> 💡 **Giải thích:** Trước khi có thể chạy một ứng dụng Flutter lần đầu, máy tính bắt buộc phải được cài đặt Flutter SDK và cấu hình môi trường phát triển.


**Câu 62. Why is immutability important in BLoC states?**  
- A. UI speed  
- **B. Predictable state changes**  
- C. Memory usage  
- D. Theme control  
*-> Đáp án: B*
> 💡 **Giải thích:** Tính bất biến (Immutability) trong BLoC States đảm bảo mỗi trạng thái mới phát ra là độc lập, giúp việc so sánh trạng thái trước/sau rõ ràng và dự đoán được (Predictable state changes).


**Câu 63. Which HTTP header is commonly used for authorization?**  
- A. Content-Type  
- B. Accept  
- **C. Authorization**  
- D. Cache-Control  
*-> Đáp án: C*
> 💡 **Giải thích:** Header 'Authorization' (ví dụ: Authorization: Bearer <token>) là chuẩn HTTP phổ biến nhất để gửi token xác thực của người dùng lên server.


**Câu 64. Which method retrieves data from SharedPreferences?**  
- **A. get()**  
- B. read()  
- C. fetch()  
- D. load()  
*-> Đáp án: A*
> 💡 **Giải thích:** Đối tượng SharedPreferences cung cấp các phương thức như getInt(), getString(), getBool() hoặc phương thức tổng quát get() để đọc dữ liệu đã lưu.


**Câu 65. Why should state be kept as local as possible?**  
- A. Better animations  
- **B. Reduce unnecessary rebuilds**  
- C. Simplify UI  
- D. Improve navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Giữ state ở phạm vi cục bộ nhất có thể giúp giảm thiểu số lượng widget bị rebuild không cần thiết, tối ưu hóa hiệu năng và đơn giản hóa việc debug.


**Câu 66. What is the primary responsibility of the setState() method?**  
- A. Persist data  
- **B. Trigger widget rebuild**  
- C. Navigate screens  
- D. Handle async tasks  
*-> Đáp án: B*
> 💡 **Giải thích:** Trách nhiệm chính của setState() là thông báo cho framework biết nội tại của State object đã thay đổi, từ đó kích hoạt widget rebuild lại UI.


**Câu 67. Why are forms important in mobile applications?**  
- A. UI decoration  
- **B. User data collection**  
- C. State management  
- D. Navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Biểu mẫu (Forms) là thành phần then chốt trong ứng dụng di động để thu thập dữ liệu đầu vào từ người dùng (User data collection) một cách có kiểm soát.


**Câu 68. What does golden testing verify?**  
- A. API responses  
- **B. UI appearance consistency**  
- C. Database state  
- D. Authentication  
*-> Đáp án: B*
> 💡 **Giải thích:** Golden Test (Snapshot testing) so sánh giao diện render thực tế của widget với một hình ảnh chuẩn (Golden image) để đảm bảo giao diện không bị sai lệch hiển thị.


**Câu 69. Which Flutter tool helps debug network requests?**  
- **A. DevTools**  
- B. Inspector  
- C. Emulator  
- D. Hot reload  
*-> Đáp án: A*
> 💡 **Giải thích:** Bộ công cụ Flutter DevTools cung cấp tab Network chuyên dụng để soi chi tiết các request HTTP, xem header, body, mã phản hồi và thời gian tải.


**Câu 70. What is the main purpose of the Container widget?**  
- A. Navigation  
- **B. Layout, styling, and positioning**  
- C. State management  
- D. Network requests  
*-> Đáp án: B*
> 💡 **Giải thích:** Container là một widget đa năng kết hợp vẽ layout, căn chỉnh lề (padding, margin), trang trí nền, bo góc, đổ bóng và định kích thước.


**Câu 71. Which Flutter plugin provides SQLite support?**  
- A. hive  
- B. moor  
- **C. sqlite**  
- D. shared_preferences  
*-> Đáp án: C*
> 💡 **Giải thích:** Plugin sqflite cung cấp các API để làm việc trực tiếp với cơ sở dữ liệu SQLite trên Android và iOS trong Flutter.


**Câu 72. What is the main benefit of Flutter's widget-based architecture?**  
- A. Widgets are only used for layout design  
- **B. Widgets allow code reuse across platforms**  
- C. Widgets automatically manage databases  
- D. Widgets replace backend services  
*-> Đáp án: B*
> 💡 **Giải thích:** Kiến trúc Widget-based của Flutter cho phép tái sử dụng các khối UI linh hoạt trên nhiều màn hình và đa nền tảng (Android, iOS, Web, Desktop).


**Câu 73. Which widget reacts to async data from local storage?**  
- **A. FutureBuilder**  
- B. StreamBuilder  
- C. ListView  
- D. Provider  
*-> Đáp án: A*
> 💡 **Giải thích:** FutureBuilder lắng nghe một Future bất đồng bộ (chẳng hạn đọc từ SharedPreferences hoặc SQLite) và tự động cập nhật UI dựa trên ConnectionState (waiting, done).


**Câu 74. What is Flutter primarily used for?**  
- A. Designing databases for mobile apps  
- **B. Creating native applications from a single codebase**  
- C. Developing server-side applications only  
- D. Building operating systems for mobile devices  
*-> Đáp án: B*
> 💡 **Giải thích:** Flutter là framework UI đa nền tảng cho phép tạo ứng dụng native chất lượng cao cho iOS, Android, Web, Desktop từ một codebase duy nhất.


**Câu 75. Which practice improves API security?**  
- A. Hardcoding keys  
- **B. Using HTTPS**  
- C. Ignoring errors  
- D. Using globals  
*-> Đáp án: B*
> 💡 **Giải thích:** Sử dụng HTTPS đảm bảo toàn bộ dữ liệu trao đổi giữa ứng dụng và máy chủ được mã hóa qua SSL/TLS, ngăn chặn kẻ xấu nghe lén hoặc đánh cắp thông tin.


**Câu 76. What does status code 200 indicate?**  
- A. Client error  
- B. Server error  
- **C. Success**  
- D. Redirect  
*-> Đáp án: C*
> 💡 **Giải thích:** Mã trạng thái HTTP 200 (OK) thể hiện yêu cầu đã được máy chủ tiếp nhận và xử lý thành công (Success).


**Câu 77. Which widget pattern protects authenticated routes?**  
- A. Navigator  
- **B. Guard**  
- C. Route protection  
- D. Middleware  
*-> Đáp án: B*
> 💡 **Giải thích:** Mô hình Route Guard (Route protection) kiểm tra trạng thái xác thực trước khi cho phép người dùng điều hướng vào các màn hình được bảo vệ.


**Câu 78. Which widget allows both scrolling and app bars to interact?**  
- A. ListView  
- **B. CustomScrollView**  
- C. GridView  
- D. Stack  
*-> Đáp án: B*
> 💡 **Giải thích:** CustomScrollView cho phép kết hợp nhiều sliver khác nhau (như SliverAppBar có hiệu ứng co giãn và SliverList) cùng cuộn mượt mà trong một viewport.


**Câu 79. Which method resets all form fields?**  
- A. clear()  
- **B. reset()**  
- C. dispose()  
- D. remove()  
*-> Đáp án: B*
> 💡 **Giải thích:** Gọi phương thức FormState.reset() sẽ đưa tất cả các FormField trong form về lại giá trị ban đầu và xóa bỏ các thông báo lỗi xác thực hiện tại.


**Câu 80. What happens if a non-nullable variable is not initialized in Dart?**  
- A. The app runs normally  
- B. A runtime exception occurs  
- **C. A compile-time error occurs**  
- D. The value becomes null automatically  
*-> Đáp án: C*
> 💡 **Giải thích:** Với cơ chế Sound Null Safety trong Dart, việc khai báo một biến non-nullable mà không khởi tạo giá trị (và không có từ khóa late) sẽ gây ra lỗi ngay lúc biên dịch (Compile-time error).


**Câu 81. Which platforms can Flutter applications target using a single codebase?**  
- A. Android only  
- B. iOS only  
- **C. Android, iOS, web, and desktop**  
- D. Web servers only  
*-> Đáp án: C*
> 💡 **Giải thích:** Flutter hỗ trợ xuất bản ứng dụng đa nền tảng từ một codebase duy nhất: bao gồm Android, iOS, Web và Desktop (Windows, macOS, Linux).


**Câu 82. What is the role of v-sync in Flutter?**  
- A. Sync data  
- **B. Optimize animation resources**  
- C. Control layout  
- D. Handle navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** v-sync (Vertical Synchronization) giúp đồng bộ khung hình hoạt ảnh của Flutter với tần số quét của màn hình thiết bị, loại bỏ hiện tượng xé hình và tiết kiệm pin.


**Câu 83. Why is secure authentication critical in mobile apps?**  
- A. UI quality  
- **B. Protect user data**  
- C. Reduce code  
- D. Improve speed  
*-> Đáp án: B*
> 💡 **Giải thích:** Xác thực an toàn là tối quan trọng nhằm bảo vệ dữ liệu cá nhân của người dùng (Protect user data) và ngăn ngừa các hành vi truy cập trái phép vào tài khoản.


**Câu 84. Which command builds a release APK?**  
- A. flutter run  
- **B. flutter build apk**  
- C. flutter doctor  
- D. flutter clean  
*-> Đáp án: B*
> 💡 **Giải thích:** Lệnh lutter build apk là lệnh chính thức của Flutter CLI để đóng gói ứng dụng Android thành file APK ở chế độ release.


**Câu 85. Why is clean architecture beneficial?**  
- A. Fewer files  
- **B. Easier maintenance and testing**  
- C. Better UI  
- D. Faster builds  
*-> Đáp án: B*
> 💡 **Giải thích:** Clean Architecture tách biệt ứng dụng thành các tầng độc lập (Data, Domain, Presentation), giúp hệ thống dễ mở rộng, dễ bảo trì và dễ viết test (Easier maintenance and testing).


**Câu 86. Which Flutter test focuses on UI components?**  
- A. Unit test  
- **B. Widget test**  
- C. Integration test  
- D. Load test  
*-> Đáp án: B*
> 💡 **Giải thích:** Widget Test (Component test) kiểm tra việc render giao diện của một widget riêng lẻ và phản ứng của nó với các tương tác chạm, nhập liệu.


**Câu 87. Which Dart data structure is best suited for storing an ordered collection of items?**  
- A. Set  
- B. Map  
- **C. List**  
- D. Queue  
*-> Đáp án: C*
> 💡 **Giải thích:** Kiểu dữ liệu List trong Dart là một danh sách có thứ tự (ordered collection), cho phép lưu trữ và truy xuất các phần tử theo chỉ số index.


**Câu 88. Why are widgets lightweight in Flutter?**  
- A. They manage system resources  
- **B. They are immutable descriptions**  
- C. They store UI state  
- D. They handle rendering directly  
*-> Đáp án: B*
> 💡 **Giải thích:** Widget trong Flutter rất nhẹ (lightweight) vì chúng chỉ là các đối tượng cấu hình bất biến (immutable descriptions), việc render thực tế do RenderObject đảm nhận.


**Câu 89. What is implicit animation?**  
- A. Manual animation control  
- **B. Animation without controller**  
- C. API animation  
- D. Navigation animation  
*-> Đáp án: B*
> 💡 **Giải thích:** Hoạt ảnh ngầm định (Implicit Animation) là cơ chế tạo animation tự động trong Flutter mà không cần người lập trình phải tự quản lý AnimationController hay Ticker.


**Câu 90. Which Flutter concept supports reactive UI updates?**  
- A. Manual refresh  
- **B. Widget rebuilding**  
- C. Hot restart  
- D. Native callbacks  
*-> Đáp án: B*
> 💡 **Giải thích:** Mô hình giao diện phản ứng (Reactive UI) của Flutter hoạt động bằng cách xây dựng lại các widget (Widget rebuilding) mỗi khi trạng thái (State) của ứng dụng thay đổi.


**Câu 91. What is the benefit of composing widgets in Flutter?**  
- A. Faster compilation  
- **B. Better code reuse and UI consistency**  
- C. Reduced memory usage  
- D. Automatic navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Cơ chế hợp thành widget (Composition) cho phép kết hợp các widget nhỏ, đơn nhiệm thành các giao diện phức tạp, tăng tính tái sử dụng và đồng bộ giao diện.


**Câu 92. Why are const widgets recommended?**  
- A. They improve readability  
- **B. They reduce rebuild cost**  
- C. They add state  
- D. They handle navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** Khai báo constructor với từ khóa 'const' giúp Flutter chỉ khởi tạo widget đó một lần trong bộ nhớ và tái sử dụng nó, tránh việc tạo lại khi widget cha rebuild.


**Câu 93. What is the main risk of improper state management?**  
- **A. UI inconsistency**  
- B. Longer compile time  
- C. Package conflicts  
- D. Build errors  
*-> Đáp án: A*
> 💡 **Giải thích:** Quản lý trạng thái không đúng cách dễ dẫn đến việc dữ liệu giữa các màn hình bị lệch nhau, gây ra tình trạng giao diện không nhất quán (UI inconsistency).


**Câu 94. What is technical debt?**  
- A. UI lag  
- **B. Future cost of poor design decisions**  
- C. Memory usage  
- D. API limit  
*-> Đáp án: B*
> 💡 **Giải thích:** Nợ kỹ thuật (Technical Debt) là chi phí phát sinh trong tương lai khi chấp nhận viết code tạm bợ, thiết kế kém để kịp tiến độ thay vì xây dựng giải pháp bài bản.


**Câu 95. Which approach helps reduce unnecessary widget rebuilds?**  
- A. Using global variables  
- **B. Fine-grained state updates**  
- C. Hot restart  
- D. Large widgets  
*-> Đáp án: B*
> 💡 **Giải thích:** Cập nhật trạng thái chi tiết theo phạm vi hẹp (Fine-grained state updates) giúp chỉ có widget cần thiết mới bị rebuild, thay vì rebuild toàn bộ màn hình.


**Câu 96. Which action best demonstrates Flutter's reactive UI model?**  
- A. Manually updating UI elements  
- **B. Rebuilding UI in response to state changes**  
- C. Editing layout XML  
- D. Calling native APIs  
*-> Đáp án: B*
> 💡 **Giải thích:** Đặc trưng lớn nhất của mô hình Reactive UI là giao diện được xây dựng lại tự động tương ứng với sự thay đổi của trạng thái (Rebuilding UI in response to state changes).


**Câu 97. Which package supports BLoC architecture?**  
- A. provider  
- **B. flutter_bloc**  
- C. sqlflite  
- D. http  
*-> Đáp án: B*
> 💡 **Giải thích:** Package lutter_bloc cung cấp các widget chuyên dụng như BlocBuilder, BlocListener, BlocProvider để triển khai kiến trúc BLoC trong Flutter.


**Câu 98. Which widget can hide user input text when configured for password entry?**  
- **A. TextField**  
- B. ObscureText  
- C. SecureInput  
- D. PasswordField  
*-> Đáp án: A*
> 💡 **Giải thích:** Widget TextField có thuộc tính obscureText: true giúp che giấu ký tự mật khẩu người dùng nhập vào bằng các dấu chấm tròn.


**Câu 99. What is the purpose of SliverAppBar?**  
- A. Static app bar  
- **B. Scrollable flexible app bar**  
- C. Bottom navigation  
- D. Drawer control  
*-> Đáp án: B*
> 💡 **Giải thích:** SliverAppBar là thanh tiêu đề cuộn linh hoạt (collapsing / flexible app bar), có thể tự động co giãn, biến mất hoặc ghim cố định khi người dùng cuộn trang.


**Câu 100. Which HTTP method is typically used to retrieve data?**  
- A. POST  
- B. PUT  
- **C. GET**  
- D. DELETE  
*-> Đáp án: C*
> 💡 **Giải thích:** Trong REST API, phương thức HTTP GET được quy chuẩn dùng để truy vấn và lấy dữ liệu (Retrieve data) từ máy chủ.


**Câu 101. Why is Chapter 13 considered optional (Plus)?**  
- A. It replaces core concepts  
- **B. Apps can work without deep optimization**  
- C. It manages navigation  
- D. It handles authentication  
*-> Đáp án: B*
> 💡 **Giải thích:** Nội dung nâng cao (Plus/Optional) thường bao gồm các kỹ thuật tối ưu hóa chuyên sâu; ứng dụng vẫn có thể hoạt động tốt mà không bắt buộc phải áp dụng ngay.


**Câu 102. Why should authentication state be centralized?**  
- A. Reduce UI code  
- **B. Ensure consistent access control**  
- C. Improve animations  
- D. Simplify layout  
*-> Đáp án: B*
> 💡 **Giải thích:** Tập trung trạng thái xác thực về một nguồn duy nhất (Centralized Auth State) giúp kiểm soát quyền truy cập nhất quán trên toàn bộ các màn hình và API trong ứng dụng.


**Câu 103. Which Dart keyword is used to define a constant value at compile time?**  
- A. final  
- B. static  
- **C. const**  
- D. var  
*-> Đáp án: C*
> 💡 **Giải thích:** Từ khóa 'const' trong Dart dùng để khai báo một hằng số được tính toán và cố định ngay tại thời điểm biên dịch (Compile-time constant).


**Câu 104. Which status code indicates server error?**  
- A. 200  
- B. 301  
- C. 404  
- **D. 500**  
*-> Đáp án: D*
> 💡 **Giải thích:** Mã trạng thái HTTP 500 (Internal Server Error) biểu thị đã xảy ra lỗi phía máy chủ (Server error) khi xử lý yêu cầu.


**Câu 105. What is the role of events in BLoC?**  
- A. Store UI  
- **B. Trigger state changes**  
- C. Render widgets  
- D. Handle layout  
*-> Đáp án: B*
> 💡 **Giải thích:** Trong BLoC, các Sự kiện (Events) là tín hiệu đầu vào kích hoạt BLoC xử lý nghiệp vụ và phát ra trạng thái mới (Trigger state changes).


**Câu 106. Which widget allows overlapping of its child widgets?**  
- A. Column  
- B. Row  
- **C. Stack**  
- D. Expanded  
*-> Đáp án: C*
> 💡 **Giải thích:** Widget Stack cho phép xếp chồng các widget con lên nhau theo trục Z (chiều sâu không gian), phần tử khai báo sau sẽ đè lên phần tử trước.


**Câu 107. What does CurvedAnimation provide?**  
- A. Layout control  
- **B. Animation curve behavior**  
- C. State updates  
- D. Navigation  
*-> Đáp án: B*
> 💡 **Giải thích:** CurvedAnimation kết hợp với AnimationController để áp dụng đường cong chuyển động phi tuyến tính (như Curves.easeInOut, Curves.bounceIn) cho hoạt ảnh.


**Câu 108. Which type of test checks individual functions or classes?**  
- A. Widget test  
- B. Integration test  
- **C. Unit test**  
- D. System test  
*-> Đáp án: C*
> 💡 **Giải thích:** Unit Test là loại kiểm thử cấp độ thấp nhất, tập trung kiểm tra tính đúng đắn của từng hàm, phương thức hoặc class logic riêng lẻ.


**Câu 109. What is the main purpose of hot reload in Flutter?**  
- A. Improve runtime performance  
- **B. Instantly reflect code changes in UI**  
- C. Publish apps faster  
- D. Reduce memory usage  
*-> Đáp án: B*
> 💡 **Giải thích:** Tính năng Hot Reload của Flutter đưa mã code vừa sửa trực tiếp vào máy ảo Dart VM đang chạy, giúp cập nhật tức thì giao diện trong vòng chưa đầy 1 giây mà không mất trạng thái hiện tại.


**Câu 110. Which phase involves gathering requirements?**  
- A. Implementation  
- B. Design  
- **C. Analysis**  
- D. Testing  
*-> Đáp án: C*
> 💡 **Giải thích:** Giai đoạn Phân tích (Analysis / Requirements Gathering) trong quy trình phát triển phần mềm là bước đầu tiên để thu thập và làm rõ các yêu cầu của dự án.


**Câu 111. Why should database operations be asynchronous?**  
- A. Simplify syntax  
- **B. Avoid blocking UI thread**  
- C. Reduce code  
- D. Improve theme  
*-> Đáp án: B*
> 💡 **Giải thích:** Các thao tác với cơ sở dữ liệu (I/O) tốn thời gian nên bắt buộc phải thực hiện bất đồng bộ (async/await) để không làm block luồng UI chính, tránh gây giật lag ứng dụng.


**Câu 112. Which widget applies a theme to an entire Flutter application?**  
- A. Scaffold  
- B. Theme  
- **C. MaterialApp**  
- D. Container  
*-> Đáp án: C*
> 💡 **Giải thích:** MaterialApp là widget gốc cấu hình chủ đề (thông qua thuộc tính 	heme: ThemeData(...)), hệ thống định tuyến (routes) và localization cho toàn bộ ứng dụng Flutter.


**Câu 113. What is the purpose of parsing JSON?**  
- A. Encrypt data  
- **B. Convert JSON into Dart objects**  
- C. Send requests  
- D. Cache responses  
*-> Đáp án: B*
> 💡 **Giải thích:** Parsing JSON là quá trình chuyển đổi chuỗi dữ liệu định dạng JSON nhận từ API thành các đối tượng Dart có cấu trúc kiểu dữ liệu rõ ràng (Type-safe models).


**Câu 114. How can data be passed to a new screen?**  
- A. Using global variables  
- **B. Via constructor arguments**  
- C. Using ThemeData  
- D. Using Scaffold  
*-> Đáp án: B*
> 💡 **Giải thích:** Cách tiêu chuẩn và an toàn nhất để truyền dữ liệu sang một màn hình mới trong Flutter là truyền qua các tham số của hàm khởi tạo (Constructor arguments) của Widget đó.


**Câu 115. Why should animations be disposed properly?**  
- A. Improve UI  
- **B. Prevent memory leaks**  
- C. Speed up builds  
- D. Fix layout  
*-> Đáp án: B*
> 💡 **Giải thích:** AnimationController sử dụng tài nguyên phần cứng (Ticker) của hệ thống. Nếu không gọi controller.dispose() khi widget bị hủy, nó sẽ gây rò rỉ bộ nhớ (Memory leak).


**Câu 116. Which widget is best used to add fixed empty space?**  
- A. Padding  
- B. Expanded  
- **C. SizedBox**  
- D. Container  
*-> Đáp án: C*
> 💡 **Giải thích:** Widget SizedBox có kích thước cố định (width và height) là widget nhẹ nhất và tối ưu nhất để chèn một khoảng trống cố định giữa các phần tử trong Row hoặc Column.


