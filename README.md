# Goetia-Correspondences-Text-File

Goetia spirits info for the Fortune app.

```sudo dnf install fortune```

Copy the files to the corresponding directory

``` sudo cp goetia goetia.dat /usr/share/games/fortune ```

Then, use the following command in order to check if it worked:

``` fortune -f ```

If you want to see only quotes from the bookofthelaw file, use this command:

 ``` fortune goetia ``` 

You can also use Cowsay

```sudo dnf install cowsay ```

``` fortune goetia | cowsay ```
