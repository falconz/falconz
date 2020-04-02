---
layout: post
title: [Bản tin bảo mật #1] Chiến dịch VPN phishing nhắm vào những người “làm việc remote”
---

Do ảnh hưởng của covid-19, nhu cầu làm việc remote thời gian gần đây đã tăng một cách đột biến, điều này tiềm ẩn nhiều nguy cơ mới về tấn công mạng. Một số công ty đã triển khai các hệ thống VPN để đảm bảo an toàn cho nhân viên khi làm việc từ xa. Hiện nay các tin tặc đã lợi dụng kịch bản này để thực hiện gửi các email mạo danh là nhân viên IT helpdesk lừa đảo người dùng nhân viên các công ty truy cập vào trang web giả mạo để download các phần mềm VPN chứa mã độc. Dưới đây là một ví dụ của chiến dịch phishing này:
![_config.yml]({{ site.baseurl }}/images/phishing.png)

Dưới đây là một số giấu hiệu nhận biết:

#Tiêu đề thường được sử dụng:
Additional VPN Channels
Laptop protection – VPN Home access #8902
VPN Portal – Home Access Connection #4207
VPN connect from home #3718
Home connection – VPN #8243
VPN- Work from home connection #3613

#Được gửi từ các địa chỉ
VPN-Tunnel <fc352725c7574bb0b1ab90eed90aae63@organization.com>
“home_access@organization.com” <beb3c52af680437c9b6b50be33fa1059@organization.com>
“remote_VPN@organization.com.com” <f8aef903d9534d6e81690de63817dcc9@organization.com>
“Admin_support@organization.com” <321bca42270440a2b29f7dbe84511619@organization.com.com
Helpdesk_admin@organization.com
64fa3560165c4e03b7c1aeb8ddb33ed7@organization.com

#IP nơi gửi:
149.72.253.54
149.72.210.181
149.72.46.6
149.72.148.1
149.72.235.28
149.72.210.223
149.72.185.154
149.72.228.46
149.72.26.120
149.72.187.27

#Các domain giả mạo (Lưu ý không truy cập các domain này):

https[:]//thingsdoing[.]z19.web.core.windows.net/
https[:]//cmakrkp033[.]z19.web.core.windows.net/
https[:]//benching22[.]z19.web.core.windows.net/
https[:]//cmakrkp66[.]z19.web.core.windows.net/
https[:]//cmakrkp044[.]z19.web.core.windows.net/
https[:]//cmakrkp88[.]z19.web.core.windows.net/
https[:]//bbreakt88[.]z19.web.core.windows.net/
https[:]//touchg33[.]z19.web.core.windows.net/

falconz, from VSEC with love

Tham khảo: https://perception-point.io/resources/incident-reports/new-phishing-campaign-remote-working-vpn-installation/