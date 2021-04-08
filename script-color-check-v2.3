// скрипт для нахождения черного цвета в 4 краски. Такие объекты, будучи использованы в штрих-кодах, могут сделать их нечитаемыми, из-за неприводки красок и расплывания линий.

var pi = app.activeDocument.pathItems; //все геометрические объекты
var tfs = app.activeDocument.textFrames; // все текстовые объекты
var all = [].concat.call(pi, tfs); // объединяем в массив
var arr = []; //массив для обнаруженных объектов
 
var has_rich_black = false;
if (all.length > 0) { //если объектов чуть более чем нифига
    
    for (var i = 0; i < all.length - 1; i++) { //запускаем цикл
 
        var fill = all[i].fillColor; //заодно вводим переменные для заливки
        var stroke = all[i].strokeColor; //и обводки
 
        // объявляем условие для исключения. объекты с цветом равным критерию ниже - не будут выделены
 
        if (
            (fill.black == 100 &&
                fill.magenta == 50.1 &&
                fill.cyan == 50.1 &&
                fill.yellow == 50.1) ||
            (stroke.black == 100 &&
                stroke.magenta == 50.1 &&
                stroke.cyan == 50.1 &&
                stroke.yellow == 50.1)
        ) {
            has_rich_black = true;
            continue;
        }
        // основная проверка. тут проверяется диапазон значений цвета. если оно  true - объекты будут выделены   
        if (
            (fill.black >= 70 && fill.black <= 100 &&
                fill.magenta >= 1 && fill.magenta <= 100 &&
                fill.cyan >= 1 && fill.cyan <= 100 &&
                fill.yellow >= 1 && fill.yellow <= 100) ||
            (stroke.black >= 70 && stroke.black <= 100 &&
                stroke.magenta >= 1 && stroke.magenta <= 100 &&
                stroke.cyan >= 1 && stroke.cyan <= 100 &&
                stroke.yellow >= 1 && stroke.yellow <= 100)
        ) {
            arr[arr.length] = all[i]; //всё что соответствует критерию выше - добавляется в массив для последующего выделения
        }
    }
}
 
if (arr.length > 0) {
    activeDocument.selection = arr; //выделяем все объекты найденные с помощью всего скрипта
    alert("Нашел составного черного: " + arr.length + " объектов");
} else {
    alert("Не нашел составного черного");
}
 
if (has_rich_black == true) {
alert("В макете есть наш Rich Black"); }
