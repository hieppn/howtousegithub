# How to use git


## Tao mot repositoty moi

## Mo cmd va cd den thu muc du an

## git init
```
git init : bien thu muc thanh 1 repository
```

## git status
```
kiem tra co loi khong
```
## Lien ket thu muc voi git
```
git remote add origin(ten tu dat) <link cua git muon lien ket>
```

## git remote -v 
### kiem tra lai link lien ket dung chua

## Them nhung gi lam duoc vao git
```
git add --all : them cac chinh sua
git commit -m " noi dung commit"
git push origin master: dua nhung thay doi o thu muc lien ket voi git len nhanh master
```
## Khoi phuc goc file 
```
git restore <ten file> 
```
### Quay lai nhung phien ban truoc
```
git reset --hard <commit_id> : commit_id lấy được khi dùng gitk và chọn commit muốn trả về
```