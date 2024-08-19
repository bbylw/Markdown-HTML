# Markdown-HTML


```html
<div style="background-color: #1E1E1E; color: #D4D4D4; font-family: 'Consolas', 'Courier New', monospace; padding: 16px; border-radius: 3px; box-shadow: 0 2px 6px rgba(0,0,0,0.15); display: flex; position: relative;">
  <button style="position: absolute; top: 5px; right: 5px; background-color: #3C3C3C; color: #CCCCCC; border: none; border-radius: 3px; padding: 5px 10px; font-size: 12px; cursor: pointer;" onclick="copyCodeToClipboard(this)">复制代码</button>
  <pre style="margin: 0; padding: 0;">
    <code><span style="color: #858585; margin-right: 16px; user-select: none; display: inline-block; text-align: right; width: 2em;">1</span>
<span style="color: #858585; margin-right: 16px; user-select: none; display: inline-block; text-align: right; width: 2em;">2</span>
<span style="color: #858585; margin-right: 16px; user-select: none; display: inline-block; text-align: right; width: 2em;">3</span>
<span style="color: #858585; margin-right: 16px; user-select: none; display: inline-block; text-align: right; width: 2em;">4</span>
    </code>
  </pre>
  <pre style="margin: 0; padding: 0;">
    <code> function copyGeneratedHTML() {
        var html = document.getElementById(&quot;html-output&quot;).textContent;
        navigator.clipboard.writeText(html).then(() =&gt; {
            alert(&#039;Generated HTML copied to clipboard!&#039;);</code>
  </pre>
</div>
<script>
function copyCodeToClipboard(button) {
  const codeBlock = button.nextElementSibling.nextElementSibling;
  const code = codeBlock.textContent;
  navigator.clipboard.writeText(code).then(() => {
    const originalText = button.textContent;
    button.textContent = '已复制！';
    button.style.backgroundColor = '#4EC9B0';
    setTimeout(() => {
      button.textContent = originalText;
      button.style.backgroundColor = '';
    }, 2000);
  }, (err) => {
    console.error('无法复制文本: ', err);
  });
}
</script>
```
