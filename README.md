# RSAnalysis
LSB隐写是一种简单而有效的信息隐藏技术，其特点是容量大、对载体图像质量影响小，嵌入速度快。可应用于灰度图像、彩色图像、视频和音频等。

基本方法：
1、将欲嵌入的秘密信息转化为比特流；
2、逐行或逐列替换载体图像的最低比特位。

嵌入规则：
1、如果秘密信息与最低比特位相同，则不改动；
2、如果秘密信息与最低比特位不同，则使用秘密信息值代替最低比特位。

