# Ilya chudovsky
## my mail ilya.tchudovsky1@yandex.ru
Skills:
- HTML&CSS
- JavaScript(beginner)
- GitHub(beginner)
Code examples:
```
var N = prompt();
var chars = N.replace(/\s/g, '');
var RowsNumber = Math.ceil(N.length / 2);
var elem = document.querySelector("#tableb");
var table = document.createElement("table");

for(var i = 0; i < RowsNumber; i++){
    var tr = table.insertRow(i);
    for(var j = 0; j < 2; j++){
        let char = chars[i * 2 + j];
        let char = chars[i * 2 + j];
        else{
            let td = tr.insertCell(j);
            td.innerHTML = arr[k];
            if(tr.lastElementChild.classList.contains("selected")){
            td.onclick = function() {
                td.classList.add("selected");
            } }
            tr.appendChild(td);
        }
        
            
    }

    table.appendChild(tr);
    
}
elem.appendChild(table);
```

Education: Peter the Great St. Petersburg Polytechnic University(1 course), online-courses HTML&CSS and JS


level of english language - A2  Pre-Intermediate.