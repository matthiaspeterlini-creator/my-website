# My Site

Questo è il mio sito web personale creato con HTML e stilizzato usando Tailwind CSS.

- Include un'intestazione personalizzata
- Contiene un'immagine con angoli arrotondati
- Utilizza classi di spaziatura e colore

<!DOCTYPE html> <!-- Tells the browser this is an HTML5 page -->
<html> <!-- Root element that wraps everything -->
  <head> <!-- Invisible settings: title, stylesheets, metadata -->
    <script src="https://cdn.tailwindcss.com"></script>
    <title>My Page</title> <!-- Text shown in the browser tab -->
  </head>

  <body> <!-- Everything the visitor sees goes here -->
    <!-- Element 1 styled with Tailwind: Heading with blue color, large size, bold text, and bottom margin -->
    <h1 class="text-blue-500 text-3xl font-bold mb-4">Matthias</h1>
    
    <!-- Element 2 styled with Tailwind: Paragraph with dark gray color and padding -->
    <p class="text-gray-700 p-2">Hallo</p>
    
    <p>A paragraph of text</p> <!-- A paragraph of text -->
    
    <!-- Element 3 styled with Tailwind: Image with custom width (w-64) and rounded corners -->
    <img class="w-64 rounded-lg" alt="chicken" src="https://ytimg.com">
  </body>
</html>


## Preview

![Website Preview](https://cdn.hackclub.com/019f70d6-ac33-7ca6-8169-d21b0305d88f/screenshot.png)
