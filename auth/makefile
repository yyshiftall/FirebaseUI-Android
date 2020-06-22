pkg = net.shiftall.nc1_android_app
src = /Users/yy/Documents/android/FirebaseUI-Android/auth/build/outputs/aar/*.aar
dst = /Users/yy/Documents/android/FirebaseAuthenticationTrial/auth

.PHONY: aar
aar :
	gradle :auth:assemble

.PHONY: cp
cp : 
	cp -r ${src} ${dst}
