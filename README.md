# 使用文档参考hojun的官方文档
[中文文档&DOCS](https://docs.hojun.cn/sakura/docs/)

# 使用文档补充说明
   - 代码高亮异常
   在博客根目录下的_config配置中找到`highlight`如下表所示修改
   ```yaml
      highlight:
        enable: false
        line_number: false
        auto_detect: false
        tab_replace: ''
        wrap: false
        hljs: false
   ```

# 更新日志
  - 2020-4-3 （本次更新无需替换配置文件）
    - 同步hojun/hexo-theme-sakura 更新
    - 增加全站 灰白模式
  - 2020-3-14（本次更新无需替换配置文件）
    - 增加42cloud 全站访问总数量显示
  - 2020-3-13 （本次更新需要替换主题的_config.yml）
    - 增加42cloud 阅读计数器
    - 修改页脚信息支持html标记
  - 2020-3-9
    - https replace (同步 honjun/hexo-theme-sakura 更新）
    - 添加 文章页，首页文章列表，分类，标签等页面未设置特色图时使用主页背景图
  - 2020-3-8
    - 修复valine评论功能
    - 添加 一言 和 网站运行时间
