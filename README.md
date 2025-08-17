# 立信英语学习平台后端系统

一个完整的英语学习平台后端系统，支持词汇管理、用户学习跟踪、CSV文件导入导出等功能。

## 功能特性

- 📚 词汇管理（添加、编辑、删除、导入、导出）
- 📊 用户学习跟踪（掌握进度、复习计划）
- 📁 CSV文件支持（批量导入导出词汇）
- 🔐 用户认证（JWT Token）
- 🔄 智能复习系统（基于遗忘曲线）
- 📱 RESTful API设计

## 技术栈

- **Node.js** - 运行时环境
- **Express.js** - Web框架
- **MongoDB** - 数据库
- **Mongoose** - ODM
- **JWT** - 认证
- **Multer** - 文件上传
- **CSV Parser/Writer** - CSV处理

## 安装步骤

### 1. 克隆项目
```bash
git clone https://github.com/your-repo/english-learning-backend.git
cd english-learning-backend