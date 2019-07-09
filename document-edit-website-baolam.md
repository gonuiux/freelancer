# HƯỚNG DẪN SỬ DỤNG WEBSITE

## Đăng nhập

Để đăng nhập vào phần quản trị website ta đăng nhập theo link *[domain-website]/wp-login.php* 

![(https://github.com/gonuiux/website-baolam/raw/master/admin-login.png)](https://github.com/gonuiux/website-baolam/raw/master/admin-login.png)

Sau đó nhập user-adim và password vào.

## Tạo tài khoản quản trị

Tùy theo nhu cầu thì chúng ta có thể tạo thêm các tài khoản để quản trị website, hiện tại có các quyền cơ bản từ cao đến thấp như sau: Administrator, Editor, Author, Contributor, Subscriber.

Để tạo user ta vào phần quản trị Admin -> sau đó vào **"User"** -> Chọn **"Add New"** -> Sau đó điền các thông tin cơ bản của user -> Chọn **"Role"** -> Chọn **"Add New User"** 

## Post bài viết

Để tạo user ta vào phần quản trị Admin -> sau đó vào **"Post"** -> Chọn **"Add New"** -> Sau đó **"Nhập nội dung bài post vào"**

#### Những nội dung trong bài Post

- **Add Title**: đây là phần để nhập nội dung tiêu đề của bài viết.
- **Phần nội dung bài post**: tương tự như các chức năng trên Office Word bao gồm các công cụ như font chữ, màu sắc, style chữ, chèn link, căn lề, table, add hình ảnh (khi muốn chọn ảnh thì vào button **Add Media**)...
- **Phần edit layout bài post**: chức năng phần này dùng để tùy chỉnh layout bài post. Có thể dạng full width hoặc có sidebar trái, sidebar phải tùy vào mục đích sử dụng, nhưng cứ để defaul là được.
- **Phần Excerpt**: là bản tóm tắt thủ công tùy chọn nội dung mà ta có thể sử dụng trong bài post
- **Discussion**: nếu ta muốn hiện chức năng comment vào trong bài post thì ta stick vào **Allow** còn không thì cứ bỏ trống những người khác vào bài post này trong website sẽ không thể comment được.
- **Slug**: có thể xem đây như đường dẫn của bài viết
- **Author**: Chọn tác giả cho bài post này
- **Publish**: khi nội dung của bài viết đã đầy đủ ta sẽ save lại bằng cách nhấn nút Publish. Đối với những bài viết không muốn hiển thị trên website nữa thì ta có thể chỉnh sang chế độ **private** để ẩn nó đi
- **Format**: chọn định dạng của bài post
- **Categories**(Phần này quan trọng): lưu ý khi post 1 bài viết mới phải chọn đúng mục categories để bài viết có thể add đúng vào menu. Trong website của chúng ta mỗi 1 nội dung trên menu chính là 1 category nên khi tạo 1 bài viết mới hãy xem bài viết này ta muốn nó nằm ở đâu thì ta sẽ  chọn đúng category đó.
- **Tags**: những tag này ta sẽ thiết lập để sau này có thể tìm kiếm bài viết dễ dàng
- **Featured Image**: đây sẽ là ảnh baner của bài viết.

#### Quản lí các bài Post

- Đối với các bài post đã lâu không cần hiển thị hoặc là những bài ta tạo bị lỗi thì có thể **stick** vào bài post đó chọn **Trash** để dời vào phần **Trash** cho dễ quản lí.
- Hoặc có thể khôi phụ bài viết từ Trash để hiển thị trở lại bằng cách vào phần **"Trash"** chọn bài post cần phục hồi sau đó chọn **"Restore"**
- Chức năng **Edit** bài viết nếu cần chỉnh sửa
- **Quick Edit** chỉnh sửa nhanh những thông tin cơ bản
- **View** để xem bài post.

## Tạo category

Để tạo Categories ta vào phần quản trị Admin -> sau đó vào **"Post"** -> Chọn **"Categories"**  -> Nhập "Tên Categories" mà ta muốn tạo -> Nhập **"Slug"** (thường là dạng ten-categoies-khong-dau-cach-nhau-boi-dau-noi) -> Chọn **"Parent Categorie"** nếu có -> Cuối cùng chọn **"Add New Categories"** để lưu lại.

## Thiết lập menu

Menu trên website hiện tại có 2 loại là: Primary meu và Secondary menu.

Để Edit Primary meu ta vào phần quản trị Admin -> sau đó vào **"Appearance"** -> Chọn **"Menu"** -> chọn **"Primary Menu"** -> Chọn **"Select"**

Để add thêm các thành phần vào ta sẽ chọn từ **"Add menu items"** -> Chọn **Page/Post/Custom links/Categories** -> Chọn phần tử cần add vào menu -> Chọn **"Add to menu"** 

Sau khi add 1 phần tử mới vào menu ta sẽ sắp xếp lại cho đúng bằng cách -> dùng chuột trái giữ phần tử cần sắp xếp -> kéo thả đúng vào vị trí cần thêm vào -> Chọn **"Save Menu"** để hoàn tất

Đối với xóa 1 phần tử trên menu thì ta sẽ click chọn phần tử đó sau đó chọn "Remove" -> Chọn **"Save Menu"** để hoàn tất.

## Edit  header

### Phần logo

Để update hay Edit kích thước logo ta vào **"Customize"** -> Chọn **"Site Identity"** ->  Sau khi edit xong chọn **"Publish"** để lưu lại.

### Phần Primary menu

Để Edit Primary menu ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Primary Navigation"** -> Sau khi edit xong chọn **"Publish"** để lưu lại

### Phần Secondary menu

Để Edit Secondary menu ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Secondary Navigation"** -> Sau khi edit xong chọn **"Publish"** để lưu lại

## Edit  footer

### Phần Widget left

Để Edit Widget left ta vào phần quản trị Admin -> sau đó vào **"Appearance"** -> Chọn **"Widgets"** -> Chọn **"Footer Widget 1"** -> Click vào **"Custom HTML"** -> Chỉnh sửa phần nội dung phía **"sau"** địa chỉ, số điện thoại, email -> Chọn **"Done"** để lưu lại.

### Phần Widget right

Để Edit Widget left ta vào phần quản trị Admin -> sau đó vào **"Appearance"** -> Chọn **"Widgets"** -> Chọn **"Footer Widget 2"** -> Click vào **"Social Icons by WPZOOM"** -> Tại đây chúng ta sẽ add kênh Social Media mới hoặc edit lại đường link cho phù hợp, những kênh Social Media không dùng chúng ta có thể xóa nó đi -> Chọn **"Done"** để lưu lại.

### Phần Bottom footer

Để Edit Bottom Footer ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Footer"** ->  Trong phần **"Copyright"** là nội dung sẽ hiễn thị của bottom footer ta sẽ edit lại -> Sau khi edit xong chọn **"Publish"** để lưu lại

## Edit  màu sắc trong Website

Để Edit màu sắc trên website ta vào **"Customize"** -> Chọn **"Colors"** -> Ta sẽ chọn thành phần cần edit lại màu sắc -> Sau đó nhập mã màu cần edit vào  -> Sau khi edit xong chọn **"Publish"** để lưu lại

## Edit  font và size chữ

Để Edit font/style/size chữ trên website ta vào **"Customize"** -> Chọn **"Typography"** -> Ta sẽ chọn thành phần cần edit lại font chữ -> Sau đó chỉnh sửa lại kiểu chữ cho phù hợp -> Sau khi edit xong chọn **"Publish"** để lưu lại.

## Edit layout page post

Để Edit Primary menu ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Blog"** -> Tại đây ta có thể chỉnh thay đổi layout của các page post bài hoặc chi tiết từng bài post cho phù hợp -> Sau khi edit xong chọn **"Publish"** để lưu lại

## Edit trang chủ

Để Edit trang chủ đầu tiên vào phần quản trị Admin -> Chọn **“Plugin”** -> Sau đó deactive plugin “**TinyMCE Advanced”** *(lưu ý: nhớ active lại sau khi edit trang chủ nhé!)*

Chọn **“Page”** -> Chọn **“All Page”**

Sau đó chọn **“Trang chủ”** cần **Edit** 

### Phần sản phẩm, giải pháp, dịch vụ, dự án

#### Hình ảnh

Chọn vào hình ảnh ta cần chỉnh sửa -> Chọn **"Edit Image"** -> Chọn hình ảnh mới muốn update lên -> Chọn **"Select"** -> Chọn **"Update"** để lưu lại

#### Tiêu đề

Chọn đúng phần tiêu đề cần Edit -> Nhập nội dung diêu đề mới vào-> Chọn **"Update"** để lưu lại

#### Nội dung

Chọn đúng phần nội cần Edit -> Nhập nội dung diêu mới vào-> Chọn **"Update"** để lưu lại

#### Button

Chọn đúng Button cần Edit -> Nhập nội dung của Button-> Update lại link mà button này liên kết nếu cần -> Chọn "**Apply"** -> Chọn **"Update"** để lưu lại

### Phần slide post

### Phần tin tức

Phần này cứ để mặc định, những bài post mới về tin tức sẽ tự động đẩy lên đây

### Phần đối tác

#### Update hình ảnh

Chọn vào hình ảnh ta cần chỉnh sửa -> Chọn **"Edit Gallery"** -> Chọn những hình ảnh mới muốn update lên -> Chọn **"Select"** -> Chọn **"Update"** để lưu lại

#### Update link liên kết

Chọn vào hình ảnh (logo công ty đối tác) -> Chọn vào hỉnh ảnh sao cho xuất hiện icon **"liên kết hình cây kẹp giấy"** -> Click vào Icon -> Nhập link liên kết của đối tác vào -> Chọn "Apply"

## Edit trang đối tác

## Edit trang giới thiệu công ty, trang tuyển dụng

Chọn **“Post”** -> Chọn **“All Post”** -> Sau đó chọn **“Giới thiệu/Tuyển dụng”** cần **Edit** -> Update lại nội dung đúng như phần post bài viết bên trên -> Chỉnh sửa định dạng như Word -> sau đó chọn **"Publish"** để lưu lại.

## Edit trang liên hệ

#### Phần nội dung

Để Edit trang chủ đầu tiên vào phần quản trị Admin -> Chọn **“Plugin”** -> Sau đó deactive plugin “**TinyMCE Advanced”** *(lưu ý: nhớ active lại sau khi edit trang chủ nhé!)*

Chọn **“Post”** -> Chọn **“All Post”** -> Sau đó chọn **“Liên hệ”** cần **Edit** -> Chọn phần nội dung ->  Chỉnh sửa phần nội dung theo đúng ý -> sau đó chọn **"Publish"** để lưu lại

#### Phần bản đồ

Để Edit trang chủ đầu tiên vào phần quản trị Admin -> Chọn **“Plugin”** -> Sau đó deactive plugin “**TinyMCE Advanced”** *(lưu ý: nhớ active lại sau khi edit trang chủ nhé!)*

Chọn **“Post”** -> Chọn **“All Post”** -> Sau đó chọn **“Liên hệ”** cần **Edit** -> Chọn phần bản đồ ->  Chỉnh sửa lại link google map cho đúng-> sau đó chọn **"Publish"** để lưu lại.

*Lưu ý: Cách lấy link Google map*

## Thiết lập plugin song ngữ

## Setting plugin chat trực tuyến

## Backup website 

## Một số qui định về hình ảnh, nội dung trong website