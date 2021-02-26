
从 VS Code 创建文件的时候，可以不必创建中间目录，直接 New File - 'folder/filename' 即可直接自动创建中间目录。

从命令行构建自定义 Tailwind 样式

```bash
npx tailwindcss-cli build css/tailwind.css -o build/tailwind.css
```

```bash
yarn add -D tailwindcss postcss autoprefixer vite

# Generate config files:
# (`-p` is for PostCSS)
npx tailwind init -p #
```

Vite 默认以 `index.html` 为入口，并且支持自动刷新。

```html
<h1 class="text-4xl font-bold text-center text-blue-500">Hello, Tailwind!</h1>
```

如果多个元素之间需要相同的间隔，那么不必所有元素都加上 `mt-*`，可以使用 `space-y-*`。

