## Git командууд :octocat:

git командуудын тайлбар цагаан толгойн үсгийн дарааллаар. Нэмэлт мэдээллийг [https://1234.mn/course/108](https://1234.mn/course/108)

git эхнээс нь дуустал гэдэг сургалт дээр үзсэн командууд болон сурагчдын оролцоотойгоор хөгжүүлэгдэж буй репо юм.

```javascript
function test() {
  console.log("look ma’, no spaces");
}
```

## Командуудын жагсаалт :sparkles:

`git add *` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add .` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add -А` **Бүх шинэ болон өөрчлөгдсөн файлуудыг стэйжилнэ**

`git add [file.txt]` **file.txt файлыг стэйжилнэ**

`git branch` **Бүх бранчуудыг жагсаалтаар харах**

`git branch -a ` **Бүх бранчуудыг үзүүлнэ**

`git branch -r ` **Remote бранчуудыг үзүүлнэ**

`git branch -vv ` **Tracking бранчуудыг үзүүлнэ**

`git config user.name [name] ` **Өөрийн нэрийг энд тохируулна (github username байж болно)**

`git config user.email [email_address] ` **Өөрийн имэйлийг энд тохируулна (github username ээ тавьж github руу push хийнэ)**

`git reflog` **Коммитуудын түүхийг жагсаалтаар харах ** `v59|03:11`

`git remote prune [remote_name]` **Локал дээрх remote_name remote-ийг цэвэрлэнэ** `v45|07:36`

`git show [hash_code]` **Тухайн коммитын дэлгэрэнгүй мэдээллийг харуулна** `v59|03:46`
