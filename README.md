Step 1. 终端输入：ssh-keygen -t rsa -C "your_email@youremail.com 直接回车，不要输入密码！

Step 2. 注册并登陆Github，点SSH and GPG keys -> New SSH key, 粘贴id_rsa.pub中的内容。

Step 3. 终端输入：ssh -T git@github.com ，会看到就会看到：You've successfully authenticated, but GitHub does not provide shell access 。这就表示已成功连上github。
