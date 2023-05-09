# lecture_27_JS_Object
#  [Задачи ](https://github.com/schoolteacherMP/lecture_27_JS_Object/blob/main/tasks.md)  

Объекты – это ассоциативные массивы с рядом дополнительных возможностей.  

Они хранят свойства (пары ключ-значение), где:  
-  Ключи свойств должны быть строками или символами (обычно строками).  
-  Значения могут быть любого типа.  

Чтобы получить доступ к свойству, мы можем использовать:  
-  Запись через точку: obj.property.  
-  Квадратные скобки obj["property"]. Квадратные скобки позволяют взять ключ из переменной, например, obj[varWithKey].  

Дополнительные операторы:  
-  Удаление свойства: delete obj.prop.  
-  Проверка существования свойства: "key" in obj.  
-  Перебор свойств объекта: цикл for for (let key in obj).  

То, что мы изучали в этой главе, называется «простым объектом» («plain object») или просто Object.  

В JavaScript есть много других типов объектов:  
-  Array для хранения упорядоченных коллекций данных,  
-  Date для хранения информации о дате и времени,  
-  Error для хранения информации об ошибке.  
-  … и так далее.  
