| Column                                             | Description                                                                                                                                                                                                                                             |
|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| FlightDate                                         | Thời điểm chuyến bay (yyyymmdd)                                                                                                                                                                                                                                                  |
| Airline                    | Hãng hàng không                                                                                                                                                                                                                                             |
| Origin                                             | Mã sân bay khởi hành                                                                                                                                                                                                  |
| Dest                                               | Mã sân bay đích                                                                                                                                                                                            |
| Cancelled                                          | Chuyến bay có bị huỷ hay không (1=Có)                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Diverted                                           | Chuyến bay có chuyển hướng hay không(1=Có)                                                                                                                                                                                                                                  |
| CRSDepTime                                         | Giờ khởi hành dự kiến (local time: hhmm)                                   |
| DepTime                                            | Giờ khởi hành thực tế (local time: hhmm)                                                                                                                                                                                               |
| DepDelayMinutes                                    | Khoảng cách theo phút giữa giờ khởi hành dự kiến và thực tế. Nếu khởi hành sớm hơn dự kiến thì đặt là 0.                                                                                                                                                               |
| DepDelay                                           | Khoảng cách theo phút giữa giờ khởi hành dự kiến và thực tế.                                       |
| ArrTime                                            | Giờ đến thực tế (local time: hhmm)                                                                                                                                                                                                                                           |
| ArrDelayMinutes                                    |  Khoảng cách theo phút giữa giờ đến dự kiến và thực tế. Nếu đến sớm hơn dự kiến thì đặt là 0.                                                                                                                                                                                        |
| ArrDelay                                           |   Khoảng cách theo phút giữa giờ đến dự kiến và thực tế.  |
| AirTime                                            |   Thời gian trên không, theo phút                                |
| CRSElapsedTime                                     | Tổng thời gian bay dự kiến theo phút                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| ActualElapsedTime                                  | Tổng thời gian bay thực tế theo phút               |
| Distance                                           | Khoảng cách giữa các sân bay (miles)     |
| Year                                               | Năm                                       |
| Quarter                                            | Quý (1-4)                                                                                                                                                                                                                                             |
| Month                                              | Tháng                                                                                                                                                                                                                                           |
| DayofMonth                                         | Ngày trong tháng      |
| DayOfWeek                                          | Ngày trong tuần                                 |
| Marketing_Airline_Network                          |  Mã đặc trưng của Marketing Carrier. Trong trường hợp cùng một mã được sử dụng bởi nhiều nhà cung cấp, một hậu tố số sẽ được thêm vào cho những nhà cung cấp trước đó, ví dụ: PA, PA(1), PA(2).                                                      |
| Operated_or_Branded_Code_Share_Partners            | Đối tác chia sẻ mã hoạt động hoặc mang thương hiệu của nhà cung cấp báo cáo                                                                                                                                                                                                                                      |
| DOT_ID_Marketing_Airline                           | Một mã số nhận dạng do Bộ Giao thông vận tải Hoa Kỳ (US DOT) cấp để xác định duy nhất một hãng hàng không (carrier). Một hãng hàng không (carrier) duy nhất được định nghĩa là hãng nắm giữ và báo cáo theo cùng một chứng nhận DOT bất kể mã hiệu, tên gọi hoặc công ty/tập đoàn mẹ.                                  |
| IATA_Code_Marketing_Airline                        | Mã IATA: Mã này do Hiệp hội Vận tải Hàng không Quốc tế (IATA) cấp và thường được sử dụng để nhận dạng nhà vận chuyển. Tuy nhiên, mã IATA không phải lúc nào cũng duy nhất vì cùng một mã có thể được cấp cho các nhà vận chuyển khác nhau trong những thời điểm khác nhau.                                                                                                                                                                                                                            |
| Flight_Number_Marketing_Airline                    | Mã số chuyến bay                                                                                                                                                                                                                                          |
| Operating_Airline                                  | Mã đặc trưng của Airline Carrier. Trong trường hợp cùng một mã được sử dụng bởi nhiều nhà cung cấp, một hậu tố số sẽ được thêm vào cho những nhà cung cấp trước đó, ví dụ: PA, PA(1), PA(2).                                             |
| DOT_ID_Operating_Airline                           | Một mã số nhận dạng do Bộ Giao thông vận tải Hoa Kỳ (US DOT) cấp để xác định duy nhất một hãng hàng không (carrier). Một hãng hàng không (carrier) duy nhất được định nghĩa là hãng nắm giữ và báo cáo theo cùng một chứng nhận DOT bất kể mã hiệu, tên gọi hoặc công ty/tập đoàn mẹ.     |
| IATA_Code_Operating_Airline                        | Mã IATA: Mã này do Hiệp hội Vận tải Hàng không Quốc tế (IATA) cấp và thường được sử dụng để nhận dạng nhà vận chuyển. Tuy nhiên, mã IATA không phải lúc nào cũng duy nhất vì cùng một mã có thể được cấp cho các nhà vận chuyển khác nhau trong những thời điểm khác nhau.                                       |
| Tail_Number                                        | Mã định danh trên đuôi máy bay                                                                                                                                                                                            |
| Flight_Number_Operating_Airline                    | Mã số chuyến bay                                                                                                                                                                                         |
| OriginAirportID                                    | Mã định danh sân bay khởi hành là một mã nhận dạng duy nhất được Cục Giao thông vận tải Hoa Kỳ (US DOT) cấp cho từng sân bay      |
| OriginAirportSeqID                                 | Mã định danh Sequence sân bay là một mã nhận dạng duy nhất được Cục Giao thông vận tải Hoa Kỳ (US DOT) cấp cho từng sân bay                                 |
| OriginCityMarketID                                 | Mã City Market sân bay là một mã nhận dạng duy nhất được Cục Giao thông vận tải Hoa Kỳ (US DOT) cấp cho từng sân bay                                                          |
| OriginCityName                                     | Tên thành phố chứa sân bay khởi hành                                                                                                                                                                                                                              |
| OriginState                                        | Mã bang của sân bay khởi hành                                                                                                                                                                        |
| OriginStateFips                                    | Mã Fips của bang có sân bay khởi hành                                                                                                                                                                           |
| OriginStateName                                    | Tên bang, sân bay khởi hành                                                                                                                                                                           |
| OriginWac                                          | Mã số điện thoại quốc tế của sân bay khởi hành                                                                                                                                                                      |
| DestAirportID                                      | Mã định danh sân bay đích đến là một mã nhận dạng duy nhất được Cục Giao thông vận tải Hoa Kỳ (US DOT) cấp cho từng sân bay. |
| DestAirportSeqID                                   | Mã định danh Sequence sân bay đích đến là một mã nhận dạng duy nhất được Cục Giao thông vận tải Hoa Kỳ (US DOT) cấp cho từng sân bay.                           |
| DestCityMarketID                                   | Mã định danh City Market sân bay đích đến là một mã nhận dạng duy nhất được Cục Giao thông vận tải Hoa Kỳ (US DOT) cấp cho từng sân bay.                                                     |
| DestCityName                                       | Tên thành phố, sân bay đích đến                                                                                                                                                                       |
| DestState                                          | Mã bang, sân bay đích đến                                                                                                                                                                       |
| DestStateFips                                      | Mã Fips của bang, sân bay đích đến                                                                                                                                                                       |
| DestStateName                                      | Tên bang, sân bay đích đến                                                                                                                                                                       |
| DestWac                                            | Mã số điện thoại quốc tế của sân bay đích đến                                                                                                                                                                 |
| DepDel15                                           | Dấu hiệu máy bay cất cánh trễ, 15 phút thì tính (1=Yes)                                                                                                                                                                                                   |
| DepartureDelayGroups                               | Khoảng thời gian hoãn khi đến, (tính theo mỗi 15 phút)                                                                                                                                                                                                 |
| DepTimeBlk                                         | Khối thời gian đến dự kiến, Khoảng thời gian tính theo giờ                                                                                                                                                                                                              |
| TaxiOut                                            | Thời gian máy bay chạy trên đường băng đến khi cất cánh , tính theo phút                                                                                                                                                                                                                              |
| WheelsOff                                          | Thời điểm càng hạ cánh máy bay thu vào khi cất cánh  (local time: hhmm)                                                                                                                                                                                                                      |
| WheelsOn                                           | Thời điểm càng hạ cánh mở ra khi hạ cánh (local time: hhmm)                                                                                                                                                                                                                       |
| TaxiIn                                             | Thời gian máy bay chạy trên đường băng đến khi hạ cánh, tính theo phút                                                                                                                                                                                                            |
| CRSArrTime                                         | Thời gian đến dự kiến (local time: hhmm)                                                                                                                                                                                                                     |
| ArrDelay                                           | Khoảng cách thời gian theo phút giữa thời gian đến dự kiến và thực tế. Nếu đến sớm hơn thì số âm.                                                                                                                                                  |
| ArrDel15                                           | Dấu hiệu máy bay đến trễ(1=Yes)                                                                                                                                                                                                     |
| ArrivalDelayGroups                                 | Khoảng thời gian trễ khi máy bay đến (15-minutes from 180)                                                                                                                                                                                                    |
| ArrTimeBlk                                         | Khối thời gian đến dự tính, Khoảng thời gian tính theo giờ                                                                                                                                                                                                               |
| DistanceGroup                                      | Các khoảng cách theo mỗi 250 dặm, cho từng chặng bay                                                                                                                                                                                                |
| DivAirportLandings                                 | Số lần máy bay hạ cánh đến sân bay ngoài dự kiến                                                                                                                                                                                                                   |


