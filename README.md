# Anthologie des chants de lutte

> "Chanter, c’est résister !"  
Depuis des siècles, la musique accompagne les luttes sociales, les révolutions et les espoirs d’un monde plus juste. Cette anthologie explore les chansons qui ont marqué l’histoire des mouvements progressistes, ouvriers, antifascistes et révolutionnaires.  

---

## Pourquoi ?

> "La musique a toujours été un outil de contestation, un cri de ralliement pour les opprimés."  
De la Commune de Paris aux luttes actuelles, en passant par les chants révolutionnaires, le folk engagé et le rap militant, cette collection met en lumière les hymnes de la gauche.  

---

## Ajouter une chanson

Pour ajouter une chanson à cette anthologie, suivez ces étapes simples :

### 1. Clonez le dépôt GitHub  
Utilisez la commande suivante pour cloner le dépôt sur votre machine locale :  

```bash
 git clone https://github.com/anthologiedeschantsdelutte/anthologie_des_chants_de_lutte.git
```

### 2. Ajoutez une nouvelle chanson  
Créez un nouveau fichier Markdown dans le répertoire des chansons (`chants/`). Par exemple : `chanson-titre.md`.  
Utilisez la structure suivante pour chaque chanson :  

```markdown
# TITRES
``BALISE`` ``BALISE`` ``BALISE``

## Vidéo YouTube
{% embed url="https://www.youtube.com/watch?v=ID" %}

---
## Paroles (LANGUE)

> ...
> ...
...

---

## Analyse

---

## Conclusion

---

## Sources

```

### 3. Faites un commit et poussez votre ajout
Une fois votre chanson ajoutée, effectuez les étapes suivantes :  

```bash
git add chants/chanson-titre.md
git commit -m "Ajout de la chanson Titre de la chanson"
git push origin main
```

### 4. Soumettez une pull request 
Allez sur GitHub, soumettez une pull request pour que votre ajout soit validé et intégré à l'anthologie.

---

> "Sans la musique, la vie serait une erreur."  
> – Friedrich Nietzsche
