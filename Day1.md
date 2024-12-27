#Quy trình upcode và làm việc cá nhân cơ bản với branch.

##B1: tạo 1 repo trên GitHub có tạo file readme

##B2: clone cái repo đấy về máy bằng câu lệnh ``` git clone [url] ``` sau đấy chuyển vào thư mục mới clone về bằng câu lệnh ``` cd <tên thư mục> ```

##B3: sau khi cd vào thư mục rồi, thực hiện một vài thay đổi với cái thư mục đấy rồi đẩy lên GitHub theo các cú pháp
	
```bash
	git add .
	
	git commit -m "nội dung commit"

	git push 

```	

##B4: tạo 1 nhánh mới bằng câu lệnh ``` git branch [branch_name] ``` rồi chuyển vào nhánh đấy ```  git checkout [branch_name] ```

##B5: thực hiện các thay đổi ở nhánh này rồi làm tương tự ở B3

##B6: chuyển về nhánh chính (nhánh main) rồi sau đấy merge những thay đổi ở nhánh phụ bằng câu lệnh ```git merge [branch_name]``` với branch_name là tên nhánh phụ

##B7: sau khi merge xong thì push nó lên nhánh chính bằng git push