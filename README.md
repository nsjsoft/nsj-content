# nsjcontent

### https://raw.githubusercontent.com/{레포지터리사용자이름}/{레포지터리이름}/{branch}/{file_path}

```javascript
 export function playSound(name,vol) {
    const audio = new Audio('https://raw.githubusercontent.com/asa9874/Github-User-Content/main/'+name+'.mp3');
    audio.volume = vol;
    audio.play();
}
```