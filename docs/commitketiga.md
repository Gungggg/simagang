## JavaScript Fetch API Beispiel

Unten finden Sie ein grundlegendes Beispiel, wie man die **Fetch API** verwendet, um Daten von einer URL abzurufen.

```javascript
async function getData(url) {
  try {
    const response = await fetch(url);
    if (!response.ok) {
      throw new Error(`HTTP-Fehler! Status: ${response.status}`);
    }
    const data = await response.json();
    console.log(data);
  } catch (error) {
    console.error("Fehler beim Abrufen der Daten:", error);
  }
}

// Beispiel für die Verwendung:
getData('[https://api.beispiel.com/daten](https://api.beispiel.com/daten)');