 <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    ul {
      list-style-type: none;
      margin: 0;
      padding-left: 20px;
    }
    li {
      margin: 5px 0;
    }
    li::before {
      content: "📁 ";
    }
    .file::before {
      content: "📄 ";
    }
  </style>
</head>
<body>
  <h1>Структура проекта</h1>
  <ul>
    <li>project-name/
      <ul>
        <li>public/
          <ul>
            <li class="file">index.html</li>
          </ul>
        </li>
        <li>src/
          <ul>
            <li class="file">main.jsx</li>
            <li class="file">App.jsx</li>
            <li class="file">App.css</li>
            <li>components/
              <ul>
                <li class="file">Header.jsx</li>
                <li class="file">Header.css</li>
                <li class="file">Main.jsx</li>
                <li class="file">Main.css</li>
                <li class="file">Footer.jsx</li>
                <li class="file">Footer.css</li>
              </ul>
            </li>
          </ul>
        </li>
        <li class="file">package.json</li>
        <li class="file">vite.config.js</li>
      </ul>
    </li>
  </ul>
</body>
</html>

