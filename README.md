<a href="www.keepizi.com"><img src="https://www.keepizi.com/wp-content/uploads/2018/08/Logo-Keepizi_violet_mobile.png" title="Keepizi" alt="Keepizi"></a>

**Exercice de mise en ligne d'un projet AJAX via GIT**
#Ajout d'article FAVORIS
>DEs articles apparaissent pour l'utilisateur.
Au clic, l'article est ajouté aux favoris via la session . Lors du déclic l'icone favoris disparait et l'article est enlevé de la session.
>Tech AJAX, JAVASCRIPT, PHP

***N'oubliez pas de . ..*
-Si vous souhaitez lier à une base de donnée, creer votre fichier d'initialisation dans le fichier inc.
-Les articles apparaissent en "dur " dans notre index , veuillez la remplacer par les votres

Ajout de notre GIF-[![Les favoris selon Moi](https://media.giphy.com/media/mVQEwcRpxamnS/giphy.gif)]()
##Table des matieres
-[explication](#explication)
-[Remerciements](#remerciements)
---
## Explication
---
>Ajout d'une portion de code dans le READ ME
```PHP

// REtrait des favoris en SESSION
if(isset($_POST["a"]) && $_POST["a"] == "remove")
{
    foreach ($_SESSION['favorites'] as $key => $value)
    {
        if($id == $value)
        {
        unset($_SESSION['favorites'][$key]);
        }
    }
}
```
-Pour retirer les favoris de ma SESSION je regarde bien que l action demandée est un "remove";
-Je fais concorder le $id envoyé en POST avec les valeurs enregistrées en SESSION.
---
A tous les étudiants!
---
[![Veuillez visiter notre site](https://media.giphy.com/media/KctrWMQ7u9D2du0YmD/giphy.gif)]gi(https://www.keepezi.com)