# shly
JavaScript library for shly.link
# main
```js
async function main(){
    const {shly} = require('./shly');
    const url= new shly();
    let req=await url.short_url("url")
    console.log(req)
}
main()
```
