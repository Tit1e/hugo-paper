# Paper - 简洁可定制的 Hugo 博客主题
Hugo 0.164+ + Go Templates + Tailwind CSS 4 + pnpm

<directory>
archetypes/ - 默认内容原型
assets/ - Tailwind 源样式与编译后的主题样式
exampleSite/ - 主题示例站点与构建配置
i18n/ - 多语言翻译资源
images/ - README 与主题展示图片
layouts/ - 页面模板、局部模板与短代码
static/ - 图标、脚本和 favicon 等静态资源
</directory>

<config>
go.mod - Hugo Module 定义，模块路径为 github.com/nanxiaobei/hugo-paper
package.json - Tailwind 开发与 Hugo 示例站点构建脚本
theme.toml - Hugo 主题元数据
pnpm-lock.yaml - 前端依赖锁定文件
</config>
