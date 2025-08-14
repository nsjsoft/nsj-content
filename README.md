# nsjcontent

### https://raw.githubusercontent.com/{레포지터리사용자이름}/{레포지터리이름}/{branch}/{file_path}

<img src="https://github.com/user-attachments/assets/a9ef1d48-91a5-44e4-bff3-f5d4abd6ab98" width="100">
<br>
<img src="https://github.com/nsjsoft/nsj-content/blob/main/jca-architecture.png" width="100">

```javascript
 export function playSound(name,vol) {
    const audio = new Audio('https://raw.githubusercontent.com/asa9874/Github-User-Content/main/'+name+'.mp3');
    audio.volume = vol;
    audio.play();
}
```
