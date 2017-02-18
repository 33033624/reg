# reg   js过滤表情的正则</br>
``
 var ranges = [
        '\ud83c[\udf00-\udfff]', 
        '\ud83d[\udc00-\ude4f]', 
        '\ud83d[\ude80-\udeff]'
    ];
    let str ='1223dkfkfkkfkldl😛😇😎😆😛';
    str = str .replace(new RegExp(ranges.join('|'), 'g'), ''));
``
