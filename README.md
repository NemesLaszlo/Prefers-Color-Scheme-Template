# Prefers-Color-Scheme-Template
Switch between Light and Dark mode by your operating system theme. (On Windows, if you use dark theme the site going to be dark as well, and vice versa.)

Article and source about this theme: https://web.dev/prefers-color-scheme/

#####Script for test your browser supports this: 
(just copy this into your html body section, check it and delete from the file)
```javascript
    <script>
      /*check the browser supports this scheme*/
      if (window.matchMedia('prefers-color-scheme').media !== 'not all') {
        console.log('Support it!');
      }
    </script>
```