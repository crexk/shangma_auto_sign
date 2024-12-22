## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:44:23 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:50:23 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:48:08 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:46:30 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:46:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:45:51 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:45:50 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 01:05:47 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 08:27:49 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 08:26:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 08:27:55 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 08:29:04 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 08:28:10 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 08:28:21 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 08:29:15 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 08:27:56 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 08:25:18 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 08:27:27 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 08:28:58 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 08:28:15 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 09:00:17 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 08:26:15 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 08:27:12 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 08:26:05 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 08:24:45 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 08:28:22 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 08:27:19 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 08:28:25 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 08:26:57 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 08:26:54 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 08:25:48 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 08:24:19 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 08:28:07 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 08:27:19 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 08:28:25 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 08:28:27 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 08:28:33 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 08:26:44 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 08:25:51 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 08:30:28 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 08:29:28 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 08:29:59 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 08:29:03 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 08:29:10 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 08:27:20 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 08:27:29 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 08:30:38 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 08:30:01 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 08:30:59 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 08:30:47 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 08:29:54 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 08:26:58 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 08:27:30 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 08:31:31 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 08:30:04 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 08:31:21 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 08:30:45 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 08:30:02 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 08:27:33 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 08:27:49 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 08:32:17 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 08:31:05 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 08:31:22 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 08:30:37 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 08:30:25 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 08:27:03 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 08:27:31 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 08:32:16 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 08:31:02 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 08:30:02 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 08:29:36 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 08:27:49 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 08:25:07 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 08:25:14 UTC 2024
