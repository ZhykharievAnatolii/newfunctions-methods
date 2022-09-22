# newfunctions-methods
// Функция очистки строки от пробела

function middleTrim(str){
    let result=``;
    for( let index=0;index<str.length;index++){
        const char=str[index];
        if(char===` `){
            continue;
        }
        result=`${result}${char}`
        console.log(str[index]);

    }
    return result;
}
