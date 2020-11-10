Step 1. 终端输入：ssh-keygen -t rsa -C "your_email@youremail.com"
          直接回车，不要输入密码！
Step 2. 注册并登陆Github，点SSH and GPG keys -> New SSH key, 
        粘贴id_rsa.pub中的内容。
Step 3. 终端输入：ssh -T git@github.com ，会看到就会看到：You've succes-
        sfully authenticated, but GitHub does not provide shell access 。
        这就表示已成功连上github。

Step 4. 配置全局的user和email。

        git config --global user.name"your name"（your name换成你注册github时的用户名）
git config --global user.email"email@qq.com"（email换成你注册github的邮箱）

Step 5. 创建远端仓库；
Step 6. 创建本地目录；
Step 7. 进入本地目录，执行
        git init;

Step 8，建立本地与github仓库的连接
        git remote add origin git@github.com:yourName/yourRepo.git（把 your name换成你注册github时填写的名字，把yourRepo 换成在github建立的仓库的名字）

Step 9. 创建或修改文件；
Step 10. 提交文件；
Step 11. 本地仓库推送到服务器；
        git push origin master

