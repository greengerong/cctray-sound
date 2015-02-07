cctray-sound
======================

##音频

更多: http://www.aspjzy.com/Class-7.html

##cctray设置

设置cctray: http://www.wrightfully.com/using-cctray-to-monitor-jenkins-builds/

##powershell
还可以利用powershell调用window语音api：

  (New-Object –ComObject SAPI.SPVoice).Speak(“Oh, my god. you broken the build. You should fix it as possible as soon.”)
  
  
注意设置powershell脚本执行安全策略：

利用run as administrator 运行powershell，并执行：

  set-executionpolicy  Unrestricted

