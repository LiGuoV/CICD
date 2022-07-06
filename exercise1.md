>目标是更好、更快的软件开发，减少可预防的错误和更好的团队合作。
# 参考文章
https://realpython.com/python-continuous-integration/
https://fullstackopen.com/zh/part11/ci_cd_%E7%AE%80%E4%BB%8B
#### CI
经常将开发人员的修改合并到主分支
#### CD
主分支始终保持可部署的做法

#### CI设置中的一些常见步骤包括linting、testing和building。在你选择的语言的生态系统中，照顾这些步骤的具体工具是什么？你可以通过谷歌搜索答案。
[linting:flake8](https://flake8.pycqa.org/)  
[testing:pytest](https://docs.pytest.org/)  

#### 除了Jenkins和GitHub Actions之外，还有什么其他方法来设置CI？同样，你可以问google!
- TravisCI
- CircleCI
#### 这样的设置在自我托管或基于云的环境中会更好吗？为什么？你需要什么信息来做这个决定？
取决于团队需要的平台和功能  
https://www.g2.com/categories/continuous-integration