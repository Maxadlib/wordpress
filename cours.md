# Worpress
## intro
- https://whatwpthemeisthat.com/
- php serialized = a:1:{s:13:"administrator";b:1;}
- aveut dire tableau, profondeur de 1, la donnée est en s :string, 13 caractères, "administrateur", b est un boléen, est 1 valide la donnée.
- https://blog.tanist.co.uk/files/unserialize/ pour déserialiser les données
- Pour créer nouvel utilisateur > ds bdd dans phpmyadmin, nouvel utilisateur, idrntifiant : 10 par exemple, login : nom de connexion, mdp > fontion  : crypté en md5. Les autres champs sont facultatifs.
- Pour définir un administrateur, aller dans la table user meta, parcourir pour voir jusqu'ou vont les umeta_id, si ça finit à 19, commencer à 20. Cliquer sur l'onglet insérer, umeta_id : 20 (si 19 le précédent), user_id : 10, meta_key : wp_capabilities, et enfin meta_value => a:1:{s:13:"administrator";b:1;} Puis cliquer sur éxécuter



    
-----------  
## Markdown code
[Markdown sur OpenClassroom](https://openclassrooms.com/fr/courses/1304236-redigez-en-markdown "markdown sur openclassroom")  
*Emphasize* _emphasize_  
**Strong** __Strong__  
A [link](http://example.com "Title").  
Some text with [a link][1] and
another [link][2].  

[1]: http://example.com/ "Title"
[2]: http://example.org/ "Title"

Logo: ![Alt](https://i2.wp.com/s.wordpress.org/about/images/logos/wordpress-logo-32.png "Title")

Smaller logo: ![Alt][1]
[1]: https://i2.wp.com/s.wordpress.org/about/images/wpmini-grey.png "Title"

Linked logo: [![alt text](https://i2.wp.com/s.wordpress.org/about/images/wpmini-grey.png)]
(http://wordpress.com/ "Title")

I have more [^1] to say up here.

[^1]: To say down here.

* Item
* Item
- Item
- Item

1. Item
2. Item

 	

3. Item
4. Item
   * Mixed
   * Mixed  
5. Item

 	

> Quoted text.
> > Quoted quote.

> * Quoted 
> * List	

  Begin each line with 
  two spaces or more to 
  make text look
  e x a c t l y 
  like  you  type i
  t.

  `This is code`

~~~~
This is a 
piece of code 
in a block
~~~~

```
This too
``` 	

```css
#button {
    border: none;
}
```

 	

# Header 1
## Header 2
### Header 3 
#### Header 4 ####
##### Header 5 #####
###### Header 6 ######

WordPress
:  A semantic personal publishing platform 

Markdown
:  Text-to-HTML conversion tool

Markdown converts text to HTML.

*[HTML]: HyperText Markup Language
