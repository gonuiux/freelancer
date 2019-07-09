# HƯỚNG DẪN SỬ DỤNG WEBSITE

## Đăng nhập

Để đăng nhập vào phần quản trị website ta đăng nhập theo link *[domain-website]/wp-login.php* 

![(https://github.com/gonuiux/website-baolam/raw/master/admin-login.png)](https://github.com/gonuiux/website-baolam/raw/master/admin-login.png)

Sau đó nhập user-adim và password vào.

## Tạo tài khoản quản trị

Tùy theo nhu cầu thì chúng ta có thể tạo thêm các tài khoản để quản trị website, hiện tại có các quyền cơ bản từ cao đến thấp như sau: Administrator, Editor, Author, Contributor, Subscriber.

Để tạo user ta vào phần quản trị Admin -> sau đó vào **"User"** -> Chọn **"Add New"** -> Sau đó điền các thông tin cơ bản của user -> Chọn **"Role"** -> Chọn **"Add New User"** 

![(https://github.com/gonuiux/website-baolam/raw/master/user-add-new.png)](https://github.com/gonuiux/website-baolam/raw/master/user-add-new.png)

## Post bài viết

Để tạo user ta vào phần quản trị Admin -> sau đó vào **"Post"** -> Chọn **"Add New"** -> Sau đó **"Nhập nội dung bài post vào"**

![(https://github.com/gonuiux/website-baolam/raw/master/post.png)](https://github.com/gonuiux/website-baolam/raw/master/post.png)

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

![(https://github.com/gonuiux/website-baolam/raw/master/post-dashboard.png)](https://github.com/gonuiux/website-baolam/raw/master/post-dashboard.png)

- Đối với các bài post đã lâu không cần hiển thị hoặc là những bài ta tạo bị lỗi thì có thể **stick** vào bài post đó chọn **Trash** để dời vào phần **Trash** cho dễ quản lí.
- Hoặc có thể khôi phụ bài viết từ Trash để hiển thị trở lại bằng cách vào phần **"Trash"** chọn bài post cần phục hồi sau đó chọn **"Restore"**
- Chức năng **Edit** bài viết nếu cần chỉnh sửa
- **Quick Edit** chỉnh sửa nhanh những thông tin cơ bản
- **View** để xem bài post.

## Tạo category

Để tạo Categories ta vào phần quản trị Admin -> sau đó vào **"Post"** -> Chọn **"Categories"**  -> Nhập "Tên Categories" mà ta muốn tạo -> Nhập **"Slug"** (thường là dạng ten-categoies-khong-dau-cach-nhau-boi-dau-noi) -> Chọn **"Parent Categorie"** nếu có -> Cuối cùng chọn **"Add New Categories"** để lưu lại.

![(https://github.com/gonuiux/website-baolam/raw/master/categories-create.png)](https://github.com/gonuiux/website-baolam/raw/master/categories-create.png)

## Thiết lập menu

Menu trên website hiện tại có 2 loại là: Primary meu và Secondary menu.

Để Edit Primary meu ta vào phần quản trị Admin -> sau đó vào **"Appearance"** -> Chọn **"Menu"** -> chọn **"Primary Menu"** -> Chọn **"Select"**

Để add thêm các thành phần vào ta sẽ chọn từ **"Add menu items"** -> Chọn **Page/Post/Custom links/Categories** -> Chọn phần tử cần add vào menu -> Chọn **"Add to menu"** 

![(https://github.com/gonuiux/website-baolam/raw/master/menu-create.png)](https://github.com/gonuiux/website-baolam/raw/master/menu-create.png)

Sau khi add 1 phần tử mới vào menu ta sẽ sắp xếp lại cho đúng bằng cách -> dùng chuột trái giữ phần tử cần sắp xếp -> kéo thả đúng vào vị trí cần thêm vào -> Chọn **"Save Menu"** để hoàn tất

Đối với xóa 1 phần tử trên menu thì ta sẽ click chọn phần tử đó sau đó chọn "Remove" -> Chọn **"Save Menu"** để hoàn tất.

**Lưu ý**: Đối với những phần tử menu nằm sâu hơn (lệch sang phải) các phần tử khác, thì phần thử đó chính là sub-menu của phần tử nằm ngoài trước nó.

![(https://github.com/gonuiux/website-baolam/raw/master/menu-level.png)](https://github.com/gonuiux/website-baolam/raw/master/menu-level.png)

## Edit  header

Cá thành phần chính của **"Header"**: Logo, Primany meu, Secondary meu ...

![(https://github.com/gonuiux/website-baolam/raw/master/header.png)](https://github.com/gonuiux/website-baolam/raw/master/header.png)

Để vào phần **"Customize"** website ta vào [domain] của trang web chọn **"Customize"**

![(https://github.com/gonuiux/website-baolam/raw/master/customize-website.png)](https://github.com/gonuiux/website-baolam/raw/master/customize-website.png)

### Phần logo

Để update hay Edit kích thước logo ta vào **"Customize"** -> Chọn **"Site Identity"** ->  Sau khi edit xong chọn **"Publish"** để lưu lại.

![(https://github.com/gonuiux/website-baolam/raw/master/customize-logo.png)](https://github.com/gonuiux/website-baolam/raw/master/customize-logo.png)

### Phần Primary menu

Để Edit Primary menu ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Primary Navigation"** -> Sau khi edit xong chọn **"Publish"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/customize-primary-menu.png)](https://github.com/gonuiux/website-baolam/raw/master/customize-primary-menu.png)

### Phần Secondary menu

Để Edit Secondary menu ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Secondary Navigation"** -> Sau khi edit xong chọn **"Publish"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/customize-second-menu.png)](https://github.com/gonuiux/website-baolam/raw/master/customize-second-menu.png)

## Edit  footer

**Footer** bao gồm các phần: Footer-left(footer bên trái), Footer-right (footer bên phải), Footer-bottom (footer bên dưới).

![(https://github.com/gonuiux/website-baolam/raw/master/footer.png)](https://github.com/gonuiux/website-baolam/raw/master/footer.png)

### Phần Widget left

Để Edit Widget left ta vào phần quản trị Admin -> sau đó vào **"Appearance"** -> Chọn **"Widgets"** -> Chọn **"Footer Widget 1"** -> Click vào **"Custom HTML"** -> Chỉnh sửa phần nội dung phía **"sau"** địa chỉ, số điện thoại, email -> Chọn **"Done"** để lưu lại.

![(https://github.com/gonuiux/website-baolam/raw/master/footer-left.png)](https://github.com/gonuiux/website-baolam/raw/master/footer-left.png)

### Phần Widget right

Để Edit Widget left ta vào phần quản trị Admin -> sau đó vào **"Appearance"** -> Chọn **"Widgets"** -> Chọn **"Footer Widget 2"** -> Click vào **"Social Icons by WPZOOM"** -> Tại đây chúng ta sẽ add kênh Social Media mới hoặc edit lại đường link cho phù hợp, những kênh Social Media không dùng chúng ta có thể xóa nó đi -> Chọn **"Done"** để lưu lại.

![(https://github.com/gonuiux/website-baolam/raw/master/footer-right.png)](https://github.com/gonuiux/website-baolam/raw/master/footer-right.png)

### Phần Bottom footer

Để Edit Bottom Footer ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Footer"** ->  Trong phần **"Copyright"** là nội dung sẽ hiễn thị của bottom footer ta sẽ edit lại -> Sau khi edit xong chọn **"Publish"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/footer-bottom.png)](https://github.com/gonuiux/website-baolam/raw/master/footer-bottom.png)

## Edit  màu sắc trong Website

Để Edit màu sắc trên website ta vào **"Customize"** -> Chọn **"Colors"** -> Ta sẽ chọn thành phần cần edit lại màu sắc -> Sau đó nhập mã màu cần edit vào  -> Sau khi edit xong chọn **"Publish"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/color.png)](https://github.com/gonuiux/website-baolam/raw/master/color.png)

## Edit  font và size chữ

Để Edit font/style/size chữ trên website ta vào **"Customize"** -> Chọn **"Typography"** -> Ta sẽ chọn thành phần cần edit lại font chữ -> Sau đó chỉnh sửa lại kiểu chữ cho phù hợp -> Sau khi edit xong chọn **"Publish"** để lưu lại.

![(https://github.com/gonuiux/website-baolam/raw/master/font.png)](https://github.com/gonuiux/website-baolam/raw/master/font.png)

## Edit layout page post

Để Edit Primary menu ta vào **"Customize"** -> Chọn **"Layout"** -> Chọn **"Blog"** -> Tại đây ta có thể chỉnh thay đổi layout của các page post bài hoặc chi tiết từng bài post cho phù hợp -> Sau khi edit xong chọn **"Publish"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/blog-layout.png)](https://github.com/gonuiux/website-baolam/raw/master/blog-layout.png)

## Edit trang chủ

Các thành phần trang chủ 

![(https://github.com/gonuiux/website-baolam/raw/master/home-page.png)](https://github.com/gonuiux/website-baolam/raw/master/home-page.png)

Để Edit trang chủ đầu tiên vào phần quản trị Admin -> Chọn **“Plugin”** -> Sau đó deactive plugin “**TinyMCE Advanced”** *(lưu ý: nhớ active lại sau khi edit trang chủ nhé!)*

![(https://github.com/gonuiux/website-baolam/raw/master/tini-plugin-deactive.png)](https://github.com/gonuiux/website-baolam/raw/master/tini-plugin-deactive.png)

Chọn **“Page”** -> Chọn **“All Page”**

![(https://github.com/gonuiux/website-baolam/raw/master/page.png)](https://github.com/gonuiux/website-baolam/raw/master/page.png)

Sau đó chọn **“Trang chủ”** cần **Edit** 

![(https://github.com/gonuiux/website-baolam/raw/master/page-trang-chu.png)](https://github.com/gonuiux/website-baolam/raw/master/page-trang-chu.png)

### Phần sản phẩm, giải pháp, dịch vụ, dự án

#### Hình ảnh

Chọn vào hình ảnh ta cần chỉnh sửa -> Chọn **"Edit Image"** -> Chọn hình ảnh mới muốn update lên -> Chọn **"Select"** -> Chọn **"Update"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/home-sp-image.png)](https://github.com/gonuiux/website-baolam/raw/master/home-sp-image.png)

#### Tiêu đề

Chọn đúng phần tiêu đề cần Edit -> Nhập nội dung diêu đề mới vào-> Chọn **"Update"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/home-sp-title.png)](https://github.com/gonuiux/website-baolam/raw/master/home-sp-title.png)

#### Nội dung

Chọn đúng phần nội cần Edit -> Nhập nội dung diêu mới vào-> Chọn **"Update"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/home-sp-content.png)](https://github.com/gonuiux/website-baolam/raw/master/home-sp-content.png)

#### Button

Chọn đúng Button cần Edit -> Nhập nội dung của Button-> Update lại link mà button này liên kết nếu cần -> Chọn "**Apply"** -> Chọn **"Update"** để lưu lại

![(https://github.com/gonuiux/website-baolam/raw/master/home-sp-button.png)](https://github.com/gonuiux/website-baolam/raw/master/home-sp-button.png)

### Phần slide post

Phần này cứ để mặc định

### Phần tin tức

Phần này cứ để mặc định, những bài post mới về tin tức sẽ tự động đẩy lên đây

### Phần đối tác

Để Edit phần đối tác ta vào phần quản trị Admin -> sau đó vào **"Smart logo"** -> Chọn **"doi-tac"**

![(https://github.com/gonuiux/website-baolam/raw/master/doi-tac.png)](https://github.com/gonuiux/website-baolam/raw/master/doi-tac.png)

#### Update hình ảnh

Để update thêm logo của các đối tác ta chọn **"Add logo"** -> Sau khi đã add xong ta save lại bằng cách chọn **"Update"**

![(https://github.com/gonuiux/website-baolam/raw/master/doi-tac-img.png)](https://github.com/gonuiux/website-baolam/raw/master/doi-tac-img.png)

#### Update link liên kết

Để khi nhấn vào logo có thể dẫn đến trang của đối tác -> chúng ta sẽ tạo liên kết cho logo đó bằng cách -> Click vào **"Icon link"** -> Sau khi xuất hiện popup edit link chúng ta sẽ nhập link liên kết của đối tác vào **"External URL"** -> sau khi update xong thì save lại -> chọn **"Update"**

![(https://github.com/gonuiux/website-baolam/raw/master/doi-tac-link.png)](https://github.com/gonuiux/website-baolam/raw/master/doi-tac-link.png)

## Edit trang giới thiệu công ty, trang tuyển dụng

Chọn **“Post”** -> Chọn **“All Post”** -> Sau đó chọn **“Giới thiệu/Tuyển dụng”** cần **Edit** -> Update lại nội dung đúng như phần post bài viết bên trên -> Chỉnh sửa định dạng như Word -> sau đó chọn **"Publish"** để lưu lại.

## Edit trang liên hệ

Chọn **“Post”** -> Chọn **“All Post”** -> Sau đó chọn **“Liên hệ”** cần **Edit** 

![(https://github.com/gonuiux/website-baolam/raw/master/lien-he.png)](https://github.com/gonuiux/website-baolam/raw/master/lien-he.png)

Sau đó chọn **"Edit with Elementor"**

![(https://github.com/gonuiux/website-baolam/raw/master/lien-he-edit.png)](https://github.com/gonuiux/website-baolam/raw/master/lien-he-edit.png)

#### Phần nội dung

Chọn phần thông tin liên hệ -> Edit nội dung tại ô **"Edit thông tin liên hệ"** -> Sau đó chọn **"Update"** để save lại

![(https://github.com/gonuiux/website-baolam/raw/master/lien-he-content-2.png)](https://github.com/gonuiux/website-baolam/raw/master/lien-he-content-2.png)

#### Phần bản đồ

Chọn phần Map -> Edit địa chỉ của công ty tại phần **"Nhập địa chỉ công ty"** -> sau đó chọn **"Update"** để save lại

![(https://github.com/gonuiux/website-baolam/raw/master/lien-he-map-2.png)](https://github.com/gonuiux/website-baolam/raw/master/lien-he-map-2.png)

## Setting plugin chat trực tuyến

## Backup website 

## Một số qui định về hình ảnh, nội dung trong website

### Hình ảnh

Để Website có thể hiện thị đẹp nhất thì chúng ta nên upload lên những hình ảnh có tỉ lệ chung đó là 16:9 hoạc 1:1 . Khi đã bảo đảm được những tỉ lệ này rồi thì website chúng ta mới có thể đẹp được. 

### Nội dung text

Khi post nội dung có 2 cách 1 là gõ trực tiếp hoặc là copy từ nơi khác paste vào, khi sử dụng cách copy+paste thì phải lưu ý clear html trước bằng cách paste tất cả nội dung vào 1 file notepad sau đó mới bỏ vào website.