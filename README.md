# 招聘网站维护指南

## 📌 如何更新岗位信息

### 1. 修改现有岗位
1. 进入仓库，打开 `jobs` 文件夹  
2. 点击要修改的岗位文件（如 `job1.html`）  
3. 点击右上角 ✏️ 铅笔图标编辑  
4. 直接修改文字内容（不要删除 `<>` 等符号）  
5. 点击底部的 `Commit changes` 保存

### 2. 添加新岗位
1. 在 `jobs` 文件夹中，点击 `Add file` → `Create new file`  
2. 输入文件名：`jobX.html`（X 用数字，如 `job11.html`）  
3. **复制模板内容**：  
   - 打开任意现有岗位文件（如 `job1.html`）  
   - 全选内容并复制  
   - 粘贴到新文件中  
4. 修改标题、薪资、职责等文字  
5. 点击 `Commit changes` 保存

### 3. 更新岗位列表
1. 打开 `index.html` 文件并编辑  
2. 找到类似下面的代码块（每个岗位一个）：  
   ```html
   <a href="jobs/job1.html" class="job-card">
       <div class="job-title">前端开发工程师</div>
       <div class="job-meta">
           <span>北京</span>
           <span class="job-salary">15k-30k</span>
       </div>
   </a>
