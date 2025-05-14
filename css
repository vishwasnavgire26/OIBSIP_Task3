function convertTemp() {
    const temp = parseFloat(document.getElementById('tempInput').value);
    const unit = document.getElementById('unitInput').value;
    const resultDiv = document.getElementById('result');
  
    if (isNaN(temp)) {
      resultDiv.innerText = 'Please enter a valid number!';
      return;
    }
  
    let c, f, k;
    if (unit === 'celsius') {
      f = (temp * 9/5) + 32;
      k = temp + 273.15;
      resultDiv.innerText = `${temp}°C = ${f.toFixed(2)}°F, ${k.toFixed(2)}K`;
    } else if (unit === 'fahrenheit') {
      c = (temp - 32) * 5/9;
      k = c + 273.15;
      resultDiv.innerText = `${temp}°F = ${c.toFixed(2)}°C, ${k.toFixed(2)}K`;
    } else if (unit === 'kelvin') {
      c = temp - 273.15;
      f = (c * 9/5) + 32;
      resultDiv.innerText = `${temp}K = ${c.toFixed(2)}°C, ${f.toFixed(2)}°F`;
    }
  }
  
