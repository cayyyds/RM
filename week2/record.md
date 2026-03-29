# 卡尔曼滤波和MPC
https://www.bilibili.com/video/BV1ez4y1X7eR/?spm_id_from=333.337.search-card.all.click&vd_source=f5dc71dce99e951e4437ffdb7af02c12，https://www.bilibili.com/video/BV1cL411n7KV/?spm_id_from=333.1387.collection.video_card.click&vd_source=f5dc71dce99e951e4437ffdb7af02c12，学习了下b站这个博主的关于卡尔曼滤波和MPC的讲解

# 自瞄算法研读
## 串口通信协议
视觉系统发送给电控的数据
1. 包头和包序号
2. 如果使用自瞄，发送开火许可、俯仰角和偏航角的变化信息;如果不使用自瞄，禁止开火，俯仰角和偏航角设置为0
3. 底盘控制数据，包含x轴、y轴的线速度和z轴的角速度，也就是沿着x轴、y轴方向平移的速度和绕z轴旋转的速度
4. 添加循环冗余校验码，保证数据的正确性