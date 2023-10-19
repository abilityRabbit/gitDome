# vue_git

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
echo "# gitDome" >> README.md
###新建项目上传
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/abilityRabbit/gitDome.git
git push -u origin main
git pull origin main

###通过http拉取代码
git remote add origin https://github.com/abilityRabbit/gitDome.git
git push -u origin main

###第一: 查看远程库的信息: git remote -v
###第二: 删除现有的远程仓库: git remote rm origin
###第三: 建立新的远程仓库地址: git remote add origin + 远程仓库地址
