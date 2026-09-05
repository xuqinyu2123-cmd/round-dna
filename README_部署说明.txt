ROUND//DNA V19.1 · GitHub Web Upload Edition

这版专门解决 GitHub 网页端上传文件数量过多的问题。

文件结构优化：
- 删除旧 scenarios 目录：72 个重复题目图片。
- 删除 focus_v19 目录：36 个重复放大图。
- 删除低清 maps 目录：8 个重复地图文件。
- 保留 8 张高清地图（maps_hd）。
- 保留 36 张每题战术 Overlay。
- 饰品和探员继续由网页资源加载，不额外增加几十个本地文件。

最终项目文件总数低于 GitHub 网页端 100 文件上传限制。

部署：
1. 解压本压缩包。
2. 打开 GitHub 的 round-dna 仓库。
3. Add file > Upload files。
4. 将解压后的全部内容拖进去。
5. Commit changes。
6. 等待 GitHub Pages 部署后访问原网页地址。
