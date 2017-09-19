# TensorFlowTryTry
TensorFlowTryTry看

建立虛擬環境

1. 切換到專案目錄 cd /d D:\git\TensorFlowTryTry

2. python -m venv TensorFlow

3. 切換到虛擬環境 TensorFlow\Scripts\activate => (如果看到前面多了 (虛擬資料夾名稱)，表示成功切換到虛擬環境)

4. 安裝TensorFlow -  pip install tensorflow

5. 安裝ipython notebook - pip install ipython notebook

6. 進入ipython notebook

7. 測試程式

	import tensorflow as tf
	
	hello = tf.constant('Hello, TensorFlow!')
	
	sess = tf.Session()
	
	print(sess.run(hello))
	
-------------------------------------------------------------------------------------------------------------------

out : b'Hello, TensorFlow!'

參考文件

http://ithelp.ithome.com.tw/articles/10187702