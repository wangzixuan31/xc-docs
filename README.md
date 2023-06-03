# 语法

Syntax is a [Tailwind UI](https://tailwindui.com) site template built using [Tailwind CSS](https://tailwindcss.com) and [Next.js](https://nextjs.org).

## 开始使用

要开始使用这个模板，首先需要安装 npm 依赖项:

```bash
npm install
cp .env.example .env.local
```

然后, 运行开发者服务:

```bash
npm run dev
```

最后, 打开 [http://localhost:3000](http://localhost:3000) 在你的浏览器打开网页.

## 个性化

你可以通过修改 /src 文件夹中的文件来开始编辑此模板。当你编辑这些文件时，网站将自动更新.

## Global search

默认情况下，此模板使用 [Algolia DocSearch](https://docsearch.algolia.com) 进行全局搜索. DocSearch 对于开源项目是免费的, 您可以在他们的网站上注册账户. 一旦您的 DocSearch 账户准备好了, 使用 Algolia 提供的值更新项目中的以下 [environment variables](https://nextjs.org/docs/basic-features/environment-variables)

```
NEXT_PUBLIC_DOCSEARCH_APP_ID=
NEXT_PUBLIC_DOCSEARCH_API_KEY=
NEXT_PUBLIC_DOCSEARCH_INDEX_NAME=
```

## 许可证

这个网站模板是一款商业产品，根据 [Tailwind UI license](https://tailwindui.com/license) 授权使用.

## 学习更多

要了解更多关于此网站模板中使用的技术，请参阅以下资源：

- [Tailwind CSS](https://tailwindcss.com/docs) - Tailwind CSS 的官方文档。
- [Next.js](https://nextjs.org/docs) - Next.js 官方文档
- [Headless UI](https://headlessui.dev) - Headless UI 的官方文档。
- [Markdoc](https://markdoc.io) - Markdoc 的官方文档
- [DocSearch](https://docsearch.algolia.com) - DocSearch 的官方文档
