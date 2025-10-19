Unzip :

```
!7z x $FILE
```

Ou en spécifiant un chemin de destination :

```
!7z x $FILE -o/content/
```

Ou en python
```
!pip install py7zr
import py7zr

archive_path = '/content/Gutenberg_philosophy_books_v1.7z'
extract_path = '/content/'

with py7zr.SevenZipFile(archive_path, mode='r') as archive:
    archive.extractall(path=extract_path)
```

Je vais répertorier ici des fichiers 7zip qui contiennent, idéalement, toute l'oeuvre d'un auteur dans une langue (principalement "fr" et "en" pour le français et l'anglais respectivement).

J'ai fais en sorte que les fichiers soient les plus cleans possibles, il n'y a donc pas de header ni de sauts de ligne au milieu d'une phrase.

Ils s'agit, pour l'essentiel, de fichiers du projet Gutenberg ou de Wikisource qui ont été cleanés.

Pou
