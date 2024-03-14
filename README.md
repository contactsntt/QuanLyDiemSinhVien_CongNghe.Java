# QuanLyDiemSinhVien_CongNghe.Java
XÂY DỰNG PHẦN MỀM QUẢN LÝ ĐIỂM SINH VIÊN
Lý do chọn đề tài
	Trong những năm gần đây, khoa học công nghệ Việt Nam đã từng bước hội nhập vào dòng chảy của khoa học công nghệ tiên tiến trên thế giới. Công nghệ thông tin ở  nước ta mới, song tốc độ phát triển của nó rất nhanh và mạnh, chiếm một vị trí quan trọng trong các ngành khoa học công nghệ. Một trong những lĩnh vực đang được ứng dụng tin học hóa rất phổ biến ở nước ta là lĩnh vực quản lý. Tin học hóa trong quản lý đã giúp cho các nhà quản lý điều hành công việc một cách khoa học, chính xác và hiệu quả.
	Quản lý điểm là một trong những công việc tương đối phức tạp, tốn nhiều thời gian và công sức. Chính vì vậy, tin học hóa trong lĩnh vực quản lí điểm là một yêu cầu tất yếu. Muốn quản lý tốt cần có được các phần mềm tốt, phần mềm phải đảm bảo được độ bảo mật cao, dễ sử dụng và nhiều tiện ích.
	Đề tài là một yêu cầu thiết thực trong quản lý của các hầu hết tất cả các trường học đang hoạt động hiện nay.
	Số lượng sinh viên đông vì vậy điểm cần nhập vào là rất nhiều, chắc chắn sẽ gây nhiều khó khăn trong việc quản lý điểm của sinh viên.
	Khó khăn trong việc cập nhật, sửa chưa điểm của sinh viên
	Khi cần tra cứu thông tin điểm của bất kỳ sinh viên nào chúng ta phải tìm, ra soát bằng phương pháp thủ công. Công việc này đòi hỏi tốn rất nhiều thời gian.
	Qua đề tài cũng là cách kiểm tra hiệu quả những kiến thức đã học và cũng là cách tiếp cận với thực tế có hiệu quả nhất đối với sinh viên.
Xuất phát từ những lợi ích nên em xin chọn đề tài “Quản lý điểm sinh viên trường Đại học X”.
Với đề tài này, em mong muốn áp dụng các kiến thức đã được học trong trường cùng với việc tìm hiểu nghiên cứu ngôn ngữ và môi trường lập trình để xây dựng một hệ thống quản lý điểm được hiệu quả.
CHƯƠNG I. TỔNG QUAN
1.1.	KHẢO SÁT THỰC TRẠNG
Hiện nay, quản lý điểm là một công việc hết sức quan trọng đối với các trường học. Công việc đó hiện đang còn làm rất thủ công tại một số trường và chính vì thế nó mang lại hiệu quả không cao. Thực tế, hiện nay trường Đại học X vẫn đang dùng hệ thống quản lý điểm trên Microsoft Excel. Công việc hằng ngày bao gồm:
•	Nhập điểm cho sinh viên, sửa chữa thông tin về điểm
•	In bảng điểm, in danh sách sinh viên đỗ, trượt, đạt học bổng…
•	Lưu trữ thông tin các bảng điểm của Sinh viên…
Công việc quản lý còn hết sức thủ công và đòi hỏi nhiều kỹ năng của người quản lý.
Ví dụ: Hằng ngày, khi người quản lý nhập đểm cho sinh viên, tính toán, in danh sách theo yêu cầu của nhà trường: những sinh viên đỗ trượt đạt học bổng…. thời gian nhập thông tin mất nhiều thời gian, việc theo dõi thống kê, tổng hợp dễ bị nhầm lẫn, khó đảm bảo độ tin cậy…
1.2.	 ĐÁNH GIÁ
 1.2.1: Nhược điểm:
•	Lưu giữ thông tin về sinh viên, giáo viên phức tạp phải sử dụng nhiều loại giấy tờ, sổ sách nên rất cồng kềnh, nơi lưu giữ không được thuận tiện, cần nhiều nhân viên.
•	Khi cần tìm kiếm thông tin về sinh viên, giáo viên sẽ mất nhiều thời gian v́à phải trực tiếp đi t́ìm các thông tin đó trong những giấy tờ sổ sách đă được ghi chép lại.
1.2.2: Ưu điểm
•	Vốn đầu tư ít tốn kém hơn, các thiết bị tin học, các phần mềm tin học cho việc quản lý không cần phải đầu tư.
Từ các ưu khuyết điểm trên dẫn đến yêu cầu phải xây dựng hệ thống mới có yêu cầu kỹ thuật, quản lý chuyên nghiệp hơn, có thể giải quyết được các khuyết điểm của hệ thống cũ.
1.3.	ĐỐI TƯỢNG VÀ PHẠM VI CỦA ỨNG DỤNG
1.3.1 Đối tượng
Hệ thống quản lý điểm được xây dựng hướng đến các đối tượng:
•	Người quản trị hệ thống
•	Cán bộ quản lý
TRƯỜNG ĐẠI HỌC HUIT	Người lập: Nguyễn Thành Tâm
Thông tin tổng quan
	Tên dự án: Phần mềm Quản lí điểm.
	Quản lí dự án:  Nguyễn Thành Tâm
Phát biểu vấn đề: 
Với số lượng sinh viên hàng năm tăng lên không ngừng, Trường Đại học Huit có nhu cầu cải tiến việc tự động lưu trữ, tìm kiếm và in ấn các báo cáo nhằm đáp ứng được một khối lượng lớn về xử lí thông tin và tính chính xác của thông tin. Sự can thiệp của hệ thống quản lí điểm sinh viênsẽ mang đến hiệu quả hoạt động cao hơn trong công tác quản lí của trường Đại học X.
Mục tiêu:
	Cho phép cán  bộ quản lí và theo dõi thông tin lí lịch, điểm của từng sinh viên, môn học  một cách chính xác.Tra cứu, thống kê kết quả,...
	Đảm bảo cơ sở dữ liệu bảo mật và có độ tin cậy cao.  
Mô tả:
	Hệ thống mới sẽ thu thập tất cả các thông tin về sinh viên, giáo viên, môn học, khoa, điểm…
	Lập danh sách, báo biểu…nhằm giúp cho cán bộ quản lí nắm rõ thông tin cần thiết. 
Lợi ích mang lại:
	Tạo sự tiện dụng, nhanh chóng và thoải mái cho các cán bộ quản lí.
	Tự động hóa cho công tác quản lí của trường tạo nên tính chuyên nghiệp cho việc quản lí thông tin.
	Tiết kiệm được thời gian và chi phí.
Các bước thực hiện để hoàn thành dự án:
	Lập kế hoạch phát triển hệ thống.
	Phân tích hệ thống.
	Thiết kế. 
	Cài đặt.
	Kiểm tra.
	Biên soạn tài liệu.
	Huấn luyện sử dụng.
1.3.3 Rằng buộc tổng quan hệ thống
•	Không ảnh hưởng đến cơ cấu tổ chức và các hệ thống khác của nhà trường.
•	Phần mềm sau khi triển khai phải đáp ứng được nhu cầu tự động 50% số lượng công việc liên quan.
•	Dữ liệu phải đúng thực tế và phải cập nhật thường xuyên.

1.4.	 MÔ TẢ PHƯƠNG ÁN TỔNG QUAN
1.4.1 Phương án lưu trữ
Cơ sở dữ liệu tập trung: là phương án đưa dữ liệu về một nơi.
Giúp quản lí chặt chẽ hơn các dữ liệu, tăng tính bảo mật vì mọi thao tác trên dữ liệu chỉ được thực hiện ở một nơi.
Tốc độ thao tác dữ liệu bị hạn chế do nhiều thao tác cùng một lúc vào một dữ liệu ở một nơi.
Ngược lại với cơ sở dữ liệu tập trung là cơ sở dữ liệu phân tán.
Cở sở dữ liệu phân tán có tốc độ thao tác dữ liệu nhanh hơn cơ sở dữ liệu tập trung.
Nhưng chi phí đầu tư tương đối cao.
Thiết kế dữ liệu tương đối khó khăn, không chặt chẽ, có thể bị lỗi không cập nhật cho tất cả các nơi lưu trữ.
Chỉ phù hợp cho cơ sở dữ liệu lớn, có khoảng cách địa lý.
Các hệ quản trị cơ sở dữ liệu : Microsoft Acces, Microsofr SQL Server, MySQL, Oracle,… 
1.4.2 Phương án khả thi
Với các mô hình dữ liệu trên, mô hình dữ liệu được áp dụng cho hệ thống là mô hình dữ liệu tập trung vì những mặt lợi sau:
Với sự phát triển công nghệ hiện nay thì tốc độ đường truyền, dung lượng bộ nhớ không là vấn đề lớn, cơ sở dữ liệu tập trung giúp ta dễ dàng sao lưu, phục hồi bảo đảm an toàn dữ liệu.
Về mặt phần cứng thì chi phí đầu tư cho mô hình này không cao.
Về mặt bảo mật dữ liệu, cần phân quyền đối với người sử dụng hệ thống, mặt khác việc quản lí được chặt chẽ hơn. 
CHƯƠNG II: CƠ SỞ LÝ THUYẾT
2.1 TỔNG QUAN VỀ JAVA
2.1.1. Môi trường lập trình
Java Development Kit (JDK - Bộ công cụ cho người phát triển ứng dụng bằng ngôn ngữ lập trình Java) là một tập hợp những công cụ phần mềm được phát triển bởi Sun Microsystems dành cho các nhà phát triển phần mềm, dùng để viết những applet Java hay những ứng dụng Java.
2.1.2 Ngôn ngữ lập trình Java
Java là một ngôn ngữ hướng đối tượng, đa mục đích với các cú pháp rất giống với C và C++. Ban đầu thì đa số mọi người nghĩ là Java sẽ chủ yếu được sử dụng để lập trình nên những applet hay những chương trình nhỏ chạy trên các trình duyệt web, tuy nhiên đến giờ thì mọi người đã thay đổi quan điểm. Một số người vốn trước đây tin rằng applet chính là đất sống của Java thì nghĩ rằng Java đã chết do sự xuất hiện của các đoạn phim hoạt hình Flash. Nhưng Java đã thay đổi. Cái thời mà người ta nghĩ rằng ứng dụng chủ yếu của Java là làm các applet động trên các trang web đã qua. Ngày nay, Sun, IBM, BEA... và các công ty khổng lồ khác đã liên kết để phát triển Java thành một môi trường đa năng chứ không chỉ dừng lại là một thứ ngôn ngữ lập trình đa nền tảng nữa. Java đã có mặt ở khắp mọi nơi: từ những chiếc điện thoại di động nhỏ bé mang nhãn hiệu Nokia, Samsung, Motorola, Ericcson..., từ các thiết bị PDA dùng hệ điều hành Palm cho đến các con chíp điện tử dùng trên các tấm thẻ tín dụng, các thiết bị chẩn đoán và phân tích dùng trong y tế, khai thác năng lượng, điểu khiển và quản lý thiết bị....từ các phần mềm trên server, các trang web động, cho đến các ứng dụng trên desktop. Bạn có biết rằng người máy Người tìm đường Sao Hỏa dùng phần mềm điều khiển bằng ngôn ngữ Java không? Nhưng điều có lẽ còn cuốn hút bạn hơn khi bạn biết rằng ngay từ năm 1997, năm mà Java còn chưa tốt như bây giờ, Trung tâm Vũ Trụ NASA đã chính thức công nhận ngôn ngữ Java là ngôn ngữ chính được sử dụng để lập trình cho các thiết bị và phần mềm dùng cho Trung tâm. 
Giờ đây, khi nhắc đến Java, người ta cần phải hiểu đó là: thứ nhất: đó là một môi trường phát triển và triển khai ứng dụng; thứ hai: đó là một ngôn ngữ lập trình toàn năng. Sự xuất hiển phổ biến của Flash không hề đe dọa đến Java. Rõ ràng với sự đầu tư của Sun và các công ty hỗ trợ Java khác, chỉ trong vòng 5 năm, nó đã trở thành một ngôn ngữ toàn năng nhất trong các ngôn ngữ lập trình được sử dụng trên thế giới hiện nay. Điều người ta quan tâm nhất ở Java là khả năng viết một lần chạy mọi nơi nghĩa là bạn có thể viết chương trình trên một máy tính cài Window, chạy chip của Intel nhưng chương trình đó vẫn chạy tốt và cho cùng một kết quả hoạt động khi chạy nó trên Macitosh hay Unix. Điều này là không tưởng đối với C, C++, VB... Khả năng chuyển đổi nền tảng, dễ phân phối, đa tầng, hướng đối tượng chính là những gì mà Java chứng tỏ nó ưu việt hơn các ngôn ngữ khác. 
Với C, C++ tức là cha mẹ đẻ của Java thì điều này là rõ ràng. Với Visual Basic, ngôn ngữ lập trình quan trọng nhất của Microsoft, ngoài những điểm vừa nói ở trên, Java còn được giới lập trình chuyên nghiệp trên thế giới trong đó các hacker thế hệ thứ nhất đánh giá rằng đây là một ngôn ngữ có cú pháp và cấu trúc tốt hơn nhiều. Sử dụng Java bạn có thể dễ dàng mở rộng dự án lập trình của mình với quy mô không giới hạn, việc quản lý cũng hết sức dễ dàng trong khi đó Visual Basic với cấu trúc thiết kế không thực sự tốt, nó chỉ thích hợp với các dự án nhỏ, ít có nhu cầu mở rộng hay quản lý. 
2.1.3 Tìm hiểu kiến trúc MVC trong Java
Kiến trúc MVC là việc chia tất cả mục của một ứng dụng ra làm ba thành phần (component) khác nhau Model, View và Controller. Các thành phần của kiến trúc MVC một trách nhiệm duy nhất và không phụ thuộc vào các thành phần khác. Những sự thay đổi trong một thành phần sẽ không có hoặc là có rất ít ảnh hưởng đến các thành phần khác. Các trách nhiệm của mỗi thành phần là - Model: Model được giao nhiệm vụ cung cấp dữ liệu cho cơ sở dữ liệu và lưu dữ liệu vào các kho chứa dữ liệu. Tất cả các nghiệp vụ logic được thực thi ở Model. Dữ liệu vào từ người dùng sẽ thông qua View được kiểm tra ở Model trước khi lưu vào cơ sở dữ liệu. Việc truy xuất, xác nhận, và lưu dữ liệu là một phần của Model
- View: View hiển thị các thông tin cho người dùng của ứng dụng và được giao nhiệm vụ cho việc nhận các dữ liệu vào từ người dùng, gửi đi các yêu cầu đến bộ điều khiển, sau đó là nhận lại các phản hồi từ bộ điều khiển và hiển kết quả cho người dùng. Các trang HTML, JSP, các thư viện thể và các file nguồn là một phần của thành phần View
- Controller: Controller là tầng trung gian giữa Model và View. Controller được giao nhiệm vụ nhận các yêu cầu từ phía máy khách. Một yêu cầu được nhận từ máy khách được thực hiện bởi một chức năng logic thích hợp từ thành phần Model và sau đó sinh ra các kết quả cho người dùng và được thành phần View hiển thị. ActionServlet, Action, ActionForm và struts-config.xml là các phần của Controller.
Với cơ sở là kiến trúc MVC, ta có thể xây dựng các ứng dụng của mình, tránh được rất nhiều những vất vả khi bảo trì, thay đổi. Những thay đổi ở mỗi thành phần thường rất ít khi ảnh hưởng đến các thành phần khác
2.2 TỔNG QUAN VỀ HỆ QUẢN TRỊ CƠ SỞ DỮ LIỆU SQL SERVER 
Thực ra thì có rất nhiều hệ quản trị cơ sở mạnh mẽ như: Oracle, My SQL…. Nhưng trong báo cáo tốt nghiệp em xin phép sử dụng SQL Server để xây dựng phần mềm.
Hệ quản trị  cơ sở dữ liệu Microsoft SQL Server (MSSQL) là một trong những hệ quản trị cơ sở dữ liệu  thông dụng hiện nay. Đây là hệ quản trị cơ sở dữ liệu thường được sử dụng với các hệ thống  trung bình, với ưu điểm  có các công cụ quản lý mạnh mẽ giúp cho việc quản lý và bảo trì hệ thống dễ dàng , hỗ trợ nhiều phương pháp lưu trữ, phân vùng và đánh chỉ mục phục vụ cho việc tối ưu hóa hiệu năng .  Với phiên bản MSSQL 2005 Microsoft đã có những cải tiến đáng kể nâng cao  hiệu năng, tính sẵn sàng của hệ thống , khả năng mở rộng và bảo mật . Phiên bản mới này còn cung cấp nhiều công cụ cho người phát triển ứng dụng được tích hợp với bộ Visual Studio do Microsoft cung cấp. Dưới đây là mô hình về các dịch vụ của SQL server.
 MSSQL  có 4 dịch vụ lớn : Database Engine,Intergration Service, Reporting service, Analysis Services. Trong phiên bản MSSQL này đã có những cải tiến đáng kể như sau.
•	DataBase Engine : được phát triển để thực thi tốt hơn với việc hỗ trợ cả dữ liệu có cấu trúc và dữ liệu phi cấu trúc( XML).
•	Khả năng sẵn sàng của hệ thống được nâng cao hơn vì MSSQL 2005 hỗ trợ các chức năng : cơ sở dữ liệu gương (Database mirroring), failover clustering , snapshots và  khôi phục dữ liệu nhanh.
•	Việc quản lý chỉ mục được thực hiện song song với việc hoạt động của hệ thống. Người dùng có thể thêm chỉ mục,  xây dựng lại chỉ mục hay xóa một chỉ mục đi trong khi hệ thống vẫn được sử dụng.
•	Chức năng phân vùng dữ liệu được hỗ trợ: Trong phiên bản này người dùng có thể phân vùng các bảng và chỉ mục cũng như quản lý  phân vùng dữ liệu  một cách dễ dàng. Việc hỗ trợ phân vùng dữ liệu giúp nâng cao hiệu năng hoạt động của hệ thống.
•	Dịch vụ  đồng bộ hóa dữ liệu được mở rộng với việc hỗ trợ mô hình đồng bộ hóa ngang hàng. Đây là dịch  giúp đồng bộ hóa dữ liệu giữa các máy chủ dữ liệu, dịch vụ này làm khả năng mở rộng của hệ thống  được nâng cao.
•	Dịch vụ tích hợp (Integration Service )  thiết kế lại cho phép người dùng tích hợp dữ liệu và phân tích dữ liệu từ nhiều nguồn khác nhau. Hỗ trợ việc quản lý chất lượng dữ liệu và làm sạch dữ liệu, một công việc quan trọng trong tiến trình ETL.
•	Dịch vụ phân tích dữ liệu (Analysis Service ): cung cấp khung nhìn tích hợp và thống nhất về dữ liệu cho người dùng, hỗ trợ việc phân tích dữ liệu .
•	Công cụ khai phá dữ liệu (Data mining ) được tích hợp hỗ trợ nhiều thuật toán khai phá dữ liệu, điều này hỗ trợ cho việc phân tích và khai phá dữ liệu  và xây dựng các hệ thống hỗ trợ ra quyết định cho người quản lý.
•	Dịch vụ xây dựng quản lý báo cáo (Reporting Service) được dựa trên nền tảng quản trị doanh nghiệp thông minh và được quản lý qua dịch vụ web. Báo cáo có thể được  xây dựng với ngôn ngữ truy vấn MDX. Việc xây dựng báo cáo dễ dàng thông qua các công cụ trên Business Intelligent, người dùng truy cập báo cáo dễ dàng và trích xuất ra nhiều định dạng khác nhau  thông qua  trình duyệt web.

CHƯƠNG III : PHÂN TÍCH VÀ THIẾT KẾ HỆ THỐNG
3.1 XÁC ĐỊNH YÊU CẦU
3.1.1 Yêu cầu chức năng
	Hệ thống phải cập nhập, lưu trữ được tất cả các thông tin chi tiết về sinh viên, điểm, danh mục,…
	Cập nhật theo danh mục: giảng viên, sinh viên, lớp, học phần,…
	Nhập điểm: Từ giảng viên, điểm thi trắc nghiệm trên máy, điểm thi trên giấy.
	Tự động xử lý điểm. (Điểm được xử lý theo quy chế của bộ Giáo Dục)
	Cung cấp, tra cứu điểm 
3.1.2 Yêu cầu hệ thống
	Hệ thống sử dụng hệ quản trị cơ sở dữ liệu đủ lớn để đáp ứng số lượng sinh viên ngày càng tăng. 
	Máy chủ có khả năng tính toán nhanh, chính xác, lưu trữ lâu dài, bảo mật. 
	Hệ thống mạng đáp ứng khả năng truy cập lớn. 
	Đưa ra tổng kết, xếp loại sinh viên qua hệ thống, tự động. 
	Thông tin có tính đồng bộ, phân quyền quản lý chặt chẽ. 
	Bảo mật tốt cho người quản trị hệ thống.
3.2 MÔ HÌNH HÓA
3.2.1 Mô hình hóa chức năng
    3.2.1.1 Biểu đồ phân rã chức  năng (BFD)
			Hình 3.1: Sơ đồ phân dã chức năng(BFD)
3.2.1.2 Biểu đồ dòng dữ liệu (DFD)
Hình 3.2 Biểu đồ mức ngữ cảnh
	Biểu đồ mức 0 
Hình 3.3. Biểu đồ mức 0

	1.   Yêu cầu sử dụng hệ thống	         15. Yêu cầu thống kê, tra cứu
	2.   Truy vấn thông tin hệ thống	         16. Truy vấn TT danh mục
	3.   Trả về thông tin hệ thống	         17. Trả về thông tin danh mục
	4.   Xác nhận sử dụng hệ thống	         18. Truy vấn điểm
	5.   Yêu cầu cập nhâp danh mục	         19. Trả về thông tin điểm
	6.   Truy vấn thông tin danh mục        20. Kết quả thống kê, tra cứu
	7.   Trả về thông tin danh mục	         21. Yêu cầu sử dụng hệ thống
	8.   Danh mục được cập nhập	         22. Xác nhận sử dụng hệ thống
	9.   Yêu cầu xử lý điểm	                   23. Yêu cầu tra cứu
	10. Truy vấn thông tin danh mục       24. Kết quả tra cứu
	11. Trả về thông tin danh mục	         25. Yêu cầu sử dụng hệ thống
	12. Truy vấn thông tin điểm	         26. Xác nhận sử dụng hệ thống
	13. Trả về thông tin điểm	                   27. Yêu cầu xử lí điểm
	14. Kết quả xử lý điểm	                   28. Kết quả xử lí điểm
	Biểu đồ mức 1
 
Hình 3.4 Biểu đồ mức 1: Quản lý hệ thống
1.	Thông tin đăng nhập
2.	Truy vấn thông tin User
3.	Kết quả đăng nhập
4.	Kết quả đăng nhập
5.	Yêu cầu đăng xuất
6.	Truy vấn thông tin User
7.	Kết quả truy vấn thông tin User
8.	Kết quả đăng xuất
 
Hình 3.5 Sơ đồ mức 1 cập nhật danh mục
1. Yêu cầu cập nhập danh mục Khoa	14. Truy vấn thông tin Sinh viên
2. Thông tin Khoa cần cập nhập	15. Kết quả truy vấn TT Sinh viên
3. Kết quả cập nhập danh mục Khoa	16.  Danh mục SV đã cập nhập
4. Danh mục Khoa đã cập nhập	17.  Yêu cầu cập nhập danh mục GV
5. Yêu cầu cập nhập danh mục Lớp	18.  Truy vấn thông tin Khoa
6. Truy vấn thông tin Khoa	19.  Kết quả truy vấn thông tin GV
7. Kết quả truy vấn thông tin Khoa	20.  Thông tin GV cần cập nhập
8. Thông tin Lớp cần cập nhập	21.  Kết quả cập nhập danh mục GV
9. Kết quả cập nhập danh mục Lớp	22.  Danh mục GV đã cập nhật
10. Danh mục Lớp đã cập nhập	23.  Yêu cầu cập nhập danh  mục môn học
11. Y/cầu cập nhập danh mục SV	24. Truy vấn thông tin  môn  học
12. Truy vấn thông tin Lớp	25. Kết quả truy vấn thông tin môn học
13. Kết quả truy vấn thông tin Lớp	26. Kết quả cập nhập danh mục  môn học
  Hình 3.6  Sơ đồ mức 1: Xử lý điểm
1.Thông tin điểm	11. Yêu cầu xác nhận điểm
2. Thông tin môn học	12. Truy vấn thông tin môn học
3. Kết quả truy vấn môn học	13. Kết quả truy vấn thông tin môn học
4. Truy vấn thông tin giáo viên	14. Truy vấn thông tin giáo viên
5. Kết quả truy vấn thông tin Sinh viên	15. Kết quả truy vấn thông tin giáo viên
6.Truy vấn thông tin Sinh viên	16. Truy vấn thông tin sinh viên
7. Kết quả truy vấn thông tin Sinh viên	17. Kết quả truy vấn thông tin sinh viên
8. Cập nhập điểm	18. Truy vấn thông tin điểm
9 .Kết quả cập nhập điểm	19. Kế quả truy vấn thông tin điểm
10. Điểm đã cập nhập	24. Kết quả xác nhận điểm


 Hình 3.7 Sơ đồ mức 1: Thống kê, tra cứu
1 Yêu cầu thống kê	12. Kết quả thống kê
2. Truy vấn thông tin Khoa	13. Yêu cầu tra cứu
3. Thông tin Khoa	14. Truy vấn thông tin điểm
4. Truy vấn thông tin điểm	15. Thông tin điểm
5. Thông tin điểm	16. Truy vấn thông tin lớp
6. Truy vấn thông tin lớp	17. Thông tin lớp
7. Thông tin lớp	18. Truy vấn thông tin sinh viên
8. Truy vấn thông tin sinh viên	19. Thông tin sinh viên
9. Thông tin sinh viên	20. Truy vấn thông tin môn học
10. Truy vấn thông tin môn học	21. Thông tin môn học
11. Thông tin môn học	22. Kết quả tra cứu


3.2.  CƠ SỞ DỮ LIỆU CỦA HỆ THỐNG




