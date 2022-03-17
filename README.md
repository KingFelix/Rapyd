![Rapyd](./rapyd-cover.png)

# Rapyd
A little project about doing stuff quickly.
Rapyd consist in two little tool that live only in a URL. Just copy and paste the links into your address bar and save them as a bookmarks in your favourites toolbar or whatever you want.

### R:Note
This tool is about rapid note taking. Just click the R:Note bookmark and start typing!

    data:text/html,<html contenteditable style="font-family:monospace; font-size:22px; caret-color:red; max-width:720px; margin:0 auto; padding:48px 24px" autofocus><head><title>Rapyd</title><link rel="icon" href="https://raw.githubusercontent.com/KingFelix/Rapyd/main/rapyd.png" sizes="any"></head></html>

### R:Task
Need a way to make a to-do quickly? Here we are! R:Task is about a quick task listing. Just click the bookmark and type your tasks. When a task is completed click on it to mark it as done. Easy!

    data:text/html,<html style="font-family:monospace; font-size:22px; max-width:720px; margin:0 auto; padding:48px 24px"><head><title>R:ToDo</title><link rel="icon" href="https://raw.githubusercontent.com/KingFelix/Rapyd/main/rapyd.png" sizes="any"></head><input autofocus onfocus = "this.style.outline = 'none'" onkeydown = "search()" style="width:100%; caret-color:red; border:0; font-family:monospace; font-size:22px;" type="text" placeholder=" Task to be done.."><div class="tasks"></div><script>function search() {if(event.key === 'Enter') { document.querySelector(".tasks").innerHTML += `<div onclick = "this.style.textDecoration = 'line-through'" class='task' style="margin:24px;">${document.querySelector("input").value}</div>`; } }</script></html>

### Tips

[Here are some tips](https://kingfelix.github.io/Rapyd/tips/) for using Rapyd to the fullest!

### Example

[https://kingfelix.github.io/Rapyd/rapyd-example.html](https://kingfelix.github.io/Rapyd/rapyd-example.html)
