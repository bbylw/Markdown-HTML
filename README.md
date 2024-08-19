# Markdown-HTML

```html
function escapeHTML(str) {
        return str.replace(/&/g, "&amp;")
                  .replace(/</g, "&lt;")
                  .replace(/>/g, "&gt;")
                  .replace(/"/g, "&quot;")
                  .replace(/'/g, "&#039;");
```

<button onclick="copyCode(this)">Copy Code</button>
<script>
function copyCode(btn) {
  var code = btn.previousElementSibling.innerText;
  navigator.clipboard.writeText(code).then(() => {
    alert('Code copied to clipboard!');
  });
}
</script>
