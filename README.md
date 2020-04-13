# puppeteer-test-pdf

## test step on masOS
- run `test-from-html.js`
- chromium print: open `node_modules/puppeteer/.local-chromium/mac-xxxxxx/chrome-mac/Chromium.app` to open `data/test-simple.html`, `Command+P` set params in the code to print and print 
- chrome print: open latest chrome(better >= 79)，open `data/test-simple.html`，`Command+P` set params in the code to prinit and print 

## macOS测试方法
- 运行`test-from-html.js`
- Chronium打印，打开`node_modules/puppeteer/.local-chromium/mac-xxxxxx/chrome-mac/Chromium.app` 并打开对应的 html文件，通过设置横版竖版，以及代码中的打印边距，勾选打印背景，去掉页眉页脚,打印出结果
- Chrome打印，打开最新版的Chrome(最好是79以上版本更接近Chromium的内容)，打开对应html，通过设置横版竖版，以及代码中的打印边距，勾选打印背景，去掉页眉页脚,打印出结果

## test result
- with chrome and the conresponding chromium with puppeteer, it result ok
- with puppeteer it result not

## 测试结果
- 用chrome和chromium来打印，结果都OK
- 用puppeteer 来生成，结果不符合预期
