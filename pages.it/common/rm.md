# rm

> Rimuovi file o directory.
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/manual/html_node/rm-invocation.html>.

- Rimuovi file:

`rm {{percorso/del/file1 percorso/del/file2 ...}}`

- Rimuovi file, senza chiedere conferma o mostrare messaggi di errore:

`rm -f {{percorso/della/directory}}`

- Rimuovi file interattivamente, chiedendo conferma prima di rimuovere ogni file:

`rm -i {{percorso/del/file1 percorso/del/file2 ...}}`

- Rimuovi file in modalità verbosa, scrivendo un messaggio a schermo per ogni file rimosso:

`rm -v {{percorso/del/file}}`

- Rimuovi ricorsivamente una directory e tutti i suoi contenuti:

`rm -r {{percorso/della/directory}}`
