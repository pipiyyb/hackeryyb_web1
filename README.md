<img width="865" height="328" alt="图片" src="https://github.com/user-attachments/assets/f4c25b61-3709-4168-a061-f3f545fd3232" /># hackeryyb_web1
1. 下载 hackeryyb.tar.gz 到指定目录下后进行解压 （适配 gzctf 平台项目）
解压到当前目录

tar -xzf hackeryyb.tar.gz
cd hackeryyb
3. 导入基础镜像
cd base_images_export
python3 import_base_images.py
4. 批量创建题目
python3 build.py
等待生成完 大概 （10-30 分钟内呢）
5. 批量查看题目和提示信息
python3 tip.py
可以进行查看辅助填充题目设置
6. 批量或者指定删除镜像
python3 delete.py
