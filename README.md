# AndreyS: Сниппеты для вставки в редактор
# Скопировать пример и вставить его помле последнего </details>
# HTML разметку сниппета вставлять вместо надписи КОД-ЗДЕСЬ


<details>  
<summary>ЗАГОЛОВОК</summary>
<div>
КОД-ЗДЕСЬ
</div>
<button onclick="let snipel = this.parentElement.children[1]; let range = document.createRange(); range.selectNode(snipel); window.getSelection().addRange(range); document.execCommand('copy');">Скопировать</button>
</details>
