Baidu Translate


----------
Parameters:

Appid -- required

Secret ---  required

to --- optional. default: en

from --- optional. default: auto



----------


e.g.

    var translate = require('baidu-translate')(AppId,Secret,to,from);

    translate("你好").then(res=>{
    	console.log(res)
    })

    // { from: 'zh',
    //  to: 'en',
    // trans_result: [ { src: '你好', dst: 'Hello,' } ] }
