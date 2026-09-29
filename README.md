<h1 align="center" style="margin: 30px 0 10px; font-weight: bold;">AdminPro</h1>
<h4 align="center">企业级中后台管理系统（Vue3 + Vite + Element Plus）</h4>
<p align="center">
	<img src="https://img.shields.io/badge/Vue-3.x-brightgreen.svg">
	<img src="https://img.shields.io/badge/Vite-6.x-orange.svg">
	<img src="https://img.shields.io/badge/Element Plus-2.x-blue.svg">
	<img src="https://img.shields.io/github/license/mashape/apistatus.svg">
</p>

## 平台简介

AdminPro 是一套基于 [RuoYi-Vue3](https://github.com/yangzongzhuan/RuoYi-Vue3)（MIT）二次开发的企业级中后台管理系统前端，开箱即用，适用于网站管理后台、会员中心、CMS、CRM、OA 等各类 Web 应用场景。

* 前端技术栈：[Vue3](https://v3.cn.vuejs.org) + [Element Plus](https://element-plus.org/zh-CN) + [Vite](https://cn.vitejs.dev) + Pinia + Vue Router + Sass。
* 本仓库为纯前端工程；如需完整前后端分离系统，可配套后端仓库 [RuoYi-Vue](https://gitee.com/y_project/RuoYi-Vue)（SpringBoot + Spring Security + JWT）。
* 未接入后端时，可正常预览登录页与 UI；接入后端后即可使用全部功能。

## 快速开始

```bash
# 环境要求：Node.js >= 18

# 克隆项目
git clone https://github.com/XingLuoHuanYu/AdminPro.git

# 进入项目目录
cd AdminPro

# 安装依赖
npm install --registry=https://registry.npmmirror.com

# 启动服务
npm run dev

# 前端访问地址 http://127.0.0.1:5173

# 构建测试环境 npm run build:stage
# 构建生产环境 npm run build:prod
```

## 内置功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
16. 缓存监控：对系统的缓存信息查询，命令统计等。
17. 在线构建器：拖动表单元素生成相应的HTML代码。
18. 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。

## 致谢

本项目基于 [RuoYi-Vue3](https://github.com/yangzongzhuan/RuoYi-Vue3) 二次开发，感谢若依开源社区的贡献。

## License

[MIT](LICENSE) © AdminPro. 基于 RuoYi-Vue3（MIT）二次开发，原始版权信息保留于 [LICENSE](LICENSE) 文件。
