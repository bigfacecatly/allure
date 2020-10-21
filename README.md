

代码拉取下来后 使用python3.8版本 
pipenv isntall 
pipenv shell
生成报告
py.test . --alluredir ./result/
生成测试报告页面
allure generate ./result/ -o ./report/ --clean
提示：
   如果没有allure需要使用brew install  allure进行安装（

生成测试报告页面
allure generate ./result/ -o ./report/ --clean
提示：
   如果没有allure需要使用brew install  allure进行安装（Mac版）Windows请自行百度
