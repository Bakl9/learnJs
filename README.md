# learnJs
  let srName = prompt('Во сколько начинаеться аперетив?');
  if (srName == 'Апер етив'){

  let pass = prompt('Ведите пароль', 999);
  if (pass == 'Aperetiv'){

    alert('Добро пожаловать');
  } else if (pass == '' || pass == null){
    alert('Не пройдешь')
  } else {
    alert('Нет входа')
  }

  } else if (srName == '' || srName == null){
    alert('Отмена')
  } else {
    alert ('Не правильное имя')
  }
