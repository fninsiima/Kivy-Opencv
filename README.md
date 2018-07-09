# Kivy-Opencv
Plyer camera, Opencv, Kivy

### Main requirements and how to run in terminal
TerminalPrompt:~$ p4a apk --private $HOME/Documents/kivy/cv2p4a --package=org.example.myapp --name "My trial" --version 0.1 --bootstrap=sdl2 --requirements=python2,kivy,plyer,android,opencv --permission CAMERA --permission WRITE_EXTERNAL_STORAGE --permission READ_EXTERNAL_STORAGE --debug

### In case of crash
$ adb devices (to show device)
$ adb logcat
