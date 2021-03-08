CV
----
1. Pavel Talkachev
2. [LinkedIn](https://www.linkedin.com/in/pavel-talkachev-0555b11a2) [Gmail](mailto:ptalkachev@gmail.com) [Вконтакте](https://vk.com/ptalkachev)
3. Студент выпускного курса факультета маркетинга и логистики БГЭУ. Есть небольшой опыт в разработке дизайна сайта. 
4. Навыки, приобретенные самостоятельно:
 * HTML и CSS; Less; 
 * основы JavaScript, основы Google Apps Script;
 * MODX, Drupal;
5. 
```javascript
  function addToDataBase() {
  var ss1 = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('Отправка данных');
  var ss2 = SpreadsheetApp.getActiveSpreadsheet().getSheetByName('DataBase');

  var lr = ss1.getLastRow();
  var lrDB = ss2.getLastRow();
  var lcDB = ss2.getLastColumn();
  
  var values = ss1.getRange(23, 1, lr-22, 13).getValues();
  var valuesDB = ss2.getRange(lrDB+1, 1, lr-22, 13).setValues(values);
  var clear = ss1.getRange(23, 1, lr-22, 13).clear({ formatOnly: true, contentsOnly: true});
}
```
6. 
7. Неоконченное высшее (маркетолог-экономист)
8. Примерный уровень английского: 
 * *письменный* B2
 * *устный* B1
