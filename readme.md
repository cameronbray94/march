# TO UPDATE PAGE

1. Open Console
2. `git status` this will check and show in red which bits you have changed
3. `git add .` this adds all your new files
4. `git commit -m "you message explaining what you changed"` this explains what these changes are should you want to understand what it was about later
5. `git push` this then pushes to your live website at Cameron.me


# Adding to Observabel

1. Update JSON
    (external links need https://, new tabs need loc:"_blank")
2. Publish
3. Click the three dots next to code, and copy 'embed' code
4. Paste from <script> to </script>
5. make sure that the line that has the observable <id=""> also has the styling class <div class="embeddedObservable"></div>

# Normal mistakes

- not closing tags...i.e - every opening tag <div> needs to have closing tag </div>
- misspelling things. i.e - the <div class="broy"> won't link to the class `.bray {}` because they are different names