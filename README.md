# hello-world
import cv2 #导入opencv库

#读取一张图片，地址不能带中文
imgviewx=cv2.imread("imgxzcy.jpg")

#创建一个窗口，中文显示会出乱码
cv2.namedWindow("a")

#显示图片，参数：（窗口标识字符串，imread读入的图像）
cv2.imshow("a",imgviewx)

#窗口等待任意键盘按键输入,0为一直等待,其他数字为毫秒数
cv2.waitKey(0)

#销毁窗口，退出程序
cv2.destroyAllWindows()
