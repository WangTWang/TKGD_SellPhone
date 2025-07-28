#  Cyber E-Commerce Frontend

Website giao diện người dùng mô phỏng một hệ thống thương mại điện tử với đầy đủ các trang chức năng: đăng nhập/đăng ký, giỏ hàng, thanh toán, lựa chọn sản phẩm, và thông tin liên hệ.

---

##  Cấu trúc thư mục

```
.
├── index.html               # Trang index dùng để redirect sang Homepage.html
├── pages/                   # Các trang chức năng chính
│   ├── Aboutus.html
│   ├── Address.html
│   ├── auth_page.html
│   ├── Blog.html
│   ├── Cart.html
│   ├── Catalog.html
│   ├── Contactus.html
│   ├── Homepage.html        # Trang chính (giao diện home)
│   ├── Payment.html
│   └── Shipping.html
├── styles/                  # CSS tương ứng cho từng trang
│   ├── productdetail.css
│   ├── style1.css
│   ├── styleaddress.css
│   ├── stylecart.css
│   ├── stylecatalog.css
│   ├── styleindex.css
│   ├── stylepayment.css
│   └── styleshipping.css
├── assets/
│   └── images/              # Thư mục chứa hình ảnh sử dụng trong trang
├── iPhone14.html            # Trang chi tiết sản phẩm (iPhone)
├── iPhone14Plus.html
├── iPhone14Pro.html
├── iPhone14ProMax.html
├── iPhone15.html
├── iPhone15Plus.html
├── iPhone15Pro.html
├── iPhone15ProMax.html
├── .gitignore
└── README.md
```

---

##  Cách deploy lên Netlify

1. Push toàn bộ project lên GitHub
2. Vào [Netlify](https://app.netlify.com/) → "Deploy Manual"
3. **Build command**: *(để trống)*
4. **Publish directory**: `.` (thư mục gốc)
5. File `index.html` sẽ tự động redirect người dùng sang `pages/Homepage.html`

---

##  Các tính năng nổi bật

-  Giao diện responsive nhiều trang
-  Chức năng giỏ hàng (sử dụng `localStorage`)
-  Tính năng thanh toán mô phỏng
-  Quản lý địa chỉ và lựa chọn phương thức vận chuyển
-  Trang đăng nhập / đăng ký
-  Chi tiết sản phẩm tương thích từng phiên bản iPhone
-  Tương thích dễ dàng để mở rộng bằng JavaScript động

---

##  Công nghệ sử dụng

- HTML5
- CSS3
- JavaScript (DOM manipulation & localStorage)
- Deploy: **Netlify**
