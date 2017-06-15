# Cloner le GitHub

Il vous faudra tout d'abords une copie du projet.

Soit télécharger le ici:

 [Cookie GitHub](https://github.com/yovanoc/Cookie)

Soit cloner le projet avec Git:

```batch
git clone https://github.com/yovanoc/Cookie.git
```


{% method %}
## Compilation

Une fois le projet ouvert dans **Visual Studio** il faudra changer **trois **variables.

**MainForm.cs**
```csharp
var DofusPath = @"C:\Users\NOM D'UTILISATEUR\AppData\Local\Ankama\Dofus";
var AccountName = "NomDeCompte";
var AccountPassword = "MotDePasse";
```

Après il vous suffit de build le projet ou de Debug et tout est bon!

![](/assets/af7e7a14a1.png)

{% endmethod %}
