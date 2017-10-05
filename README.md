# Fingerprint

仿 支付宝的指纹解锁,可输入密码验证

调用方法：FingerPrintVerify *verify = [[FingerPrintVerify alloc] init];
         [verify verifyFingerprintWithSuccessHandler:^(void){
	     //放置指纹验证成功后的代码，比如说确认支付，打开应用等
	 }];

![image](https://github.com/shaw2014/Fingerprint/blob/master/images/image1.png)
![image](https://github.com/shaw2014/Fingerprint/blob/master/images/image2.png)
![image](https://github.com/shaw2014/Fingerprint/blob/master/images/image3.png)
