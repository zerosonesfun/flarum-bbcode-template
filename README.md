# Flarum BBCode Template

This is not an installable extension. It is simply a template you can copy to create your own BBCode extension for Flarum. In the future I may add detailed instructions here. For now, all I can say is:

1. Edit extend.php - You'll see where the BBCode is (brackets), and then just below that line will be the HTML that the BBCode changes into. Above all of that is where you can add a URL to an external stylesheet and/or JavaScript.
2. Edit composer.json - Put in your GitHub username where appropriate and give the extension a name. 
3. Edit this README.
4. Add your CSS in the stylesheet inside of the assets folder. That's where you can add a JavaScript file as well.
