# cycles

1)При помощи цикла for выведите чётные числа от 2 до 10.

for (var i = 0; i < 11; i++) { 
  if(i % 2) continue;
  alert(i);
}

2)Перепишите код, заменив цикл for на while, без изменения поведения цикла.
for (let i = 0; i < 3; i++) {
  alert( `number ${i}!` );
}

let i=0;
while (i < 3){
	alert(`number ${i}!`);
	i++;
}

3)Напишите цикл, который предлагает prompt ввести число, большее 100. Если посетитель ввёл другое число – попросить ввести ещё раз, и так далее.
Цикл должен спрашивать число пока либо посетитель не введёт число, большее 100, либо не нажмёт кнопку Отмена (ESC).
Предполагается, что посетитель вводит только числа. Предусматривать обработку нечисловых строк в этой задаче необязательно.


