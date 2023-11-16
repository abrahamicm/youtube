# scripts

## listar videos del canal
~~~javascript
copy(Array.from(document.querySelectorAll("ytd-two-column-browse-results-renderer ytd-rich-item-renderer")).map(x => x.innerText.replace(/\n/g, "\t")+"\t"+x.querySelector("a").href).join("\n"))
~~~