# deploy-github-pages
This is basic deploy framework project to github pages instead static project
#### ❄️Author: Quyen Dang

#### ⏰Created at 17-06-2022

#### 🔥 Facebook: https://www.facebook.com/QuyenGiaSuJS/

#### ✨Phone: (+84)337846412

#### Setup project lên repository như bình thường

#### Tải dependency vào project:

```
npm i gh-pages --save-dev
```
#### Thêm 2 lệnh sau vào đầu script trong package.json
```
 "predeploy":"react-scripts build",
 "deploy":"gh-pages -d build",
```

#### Tạo file .env và thêm vào file như sau:
```
PUBLIC_URL="."
```

#### Chạy lệnh:
```
npm run deploy
```
#### Lên github vào github pages lấy link và trải nghiệm :<

####* Lưu ý: Khi cập nhật code xong muốn deploy tiếp bản mới thì chạy lại lệnh:
```
npm run deploy
```
