+++
date = '{{ .Date }}'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++

# kevin 测试

    这是一篇测试文章

<div class="custom-container">
  <h2>HTML 区块</h2>
  <p>这里可以使用任意 HTML 语法</p>
  <button onclick="alert('Hello Hugo')">点击测试</button>
</div>

