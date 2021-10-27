# Web-Browser
This post is about how web browser work.

How does Web Browser work ?

เว็บบราวเซอร์ คือ แอปพลิเคชั่นที่ใช้ในการเข้าถึง world wide web(www) ผ่าน Uniform Resource Locator(URL) เมื่อ
เรากรอก url แล้วกดส่ง คอมพิวเตอร์จะส่งลิ้ง url ที่เราหาให้เซิฟเวอร์เสร็จแล้วเซิฟเวอร์จะส่งข้อมูลที่มีใน url นั้นๆมาผ่าน 
HyperTextTransferProtocol(HTTP).HTTP คือภาษาที่ใช้ในการสื่อสารระหว่าง เว็บบราวเซอร์ และ เซิฟเวอร์. 
ตัวอย่าง สมสมุติว่าเราพิม url เข้าหน้า log in ของ facebook หลังจากเรากด enter ที่เราทำทั้งหมดมานั้นคือเราได้ใช้ 
method GET request ในการขอ HTML ของล็อกอินเพจ facebook จากเซิฟเวอร์ มาที่คอมพิวเตอร์ของเรา. ในบางทีเราต้องกรอก
ข้อมูลการสมัครไอดี, แบบฟอร์ม หรือ ล็อกอินส่งในกรณีที่เราต้องการปกปิดข้อมูลเช่นพาสเวิร์ด แบบนั้นเราใช้ method POST request
ในการส่งข้อมูลโดยเว็บบราวเซอร์นั้นส่งข้อมูลในรูปแบบ plain text ไปให้เซิฟเวอร์แล้วเซิฟเวอร์ก็จะไปเก็บข้อมูลไว้แล้ว
เมื่อไหร่ที่เราล็อกอินเข้าไอดีทางเซิฟเวอร์จะส่งคุกกี้แนบมาด้วยโดยคุกกี้ก็เปรียบสเหมือนไอดีการ์ดของเราโดยเซิฟเวอร์จะจดจำเราได้ผ่านคุกกี้นี้.

How does Web Browser work ?
Web Browser is an application that access to world wide web (www) through Uniform Resource Locator(URL). When
we enter URL and send it, the computer will send that URL to the server and after that server will send the data
within that URL by HyperTextTransferProtocol(HTTP). HTTP is the language that use for communicate between web browser 
and server. For example, we type url that use for facebook login page after we press enter, all we do is send the GET request
to the server asking for HTML of facebook login page to our computer. In some cases, we need to fill the form, register, or login.
In the case that we need to secure the password from being seen by others. We use method POST request for transmitting data from web 
browser in form of plain text to the server, then the server will save the data and submit the webpage back to our computer and
also attached cookie accordingly. Cookie is like ID card number that server use for classify the identity of individual.  
