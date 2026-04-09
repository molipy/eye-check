# eye-check
基于深度学习的【眼底眼疾识别】系统~2026原创+计算机毕设

## 项目介绍
本系统是一个面向眼底图像识别的 Web 应用，采用“前后端分离 + 深度学习推理”架构。前端使用 Vue3 与 Element Plus 构建交互界面，提供用户登录、图片上传、识别结果展示、历史记录查询与公告查看等功能；后端基于 Flask 搭建 RESTful API，结合 JWT 完成身份认证与接口权限控制。系统核心能力是对上传眼底图像进行四分类识别，输出预测类别、最高置信度及各类别概率分布，并将识别记录持久化数据库，便于后续追踪与统计。为满足工程可用性，系统还实现了图片格式与大小校验、静态文件访问、管理员公告管理等模块，形成了从数据输入、模型推理到结果管理的完整闭环，可用于教学演示、小规模筛查场景验证与后续功能扩展。
![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/4054ad1af2394d7981d62d8c42f09435.png)

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/2b429dbf4b9947f88e2fe26106ddbe4f.png)

![图片](https://oa-project-storage.oss-cn-hangzhou.aliyuncs.com/dbd879c9ebd14815882affed8a5f4c5d.png)



## 演示视频 and 完整代码 and 安装
地址：https://www.yuque.com/ziwu/qkqzd2/crsv8oqce8rx1z6f
