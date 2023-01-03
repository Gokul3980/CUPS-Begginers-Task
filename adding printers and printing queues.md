
# ADDING PRINTERS & CREATING PRINT QUEUES
This command was used to create the printers.
```
/usr/sbin/lpadmin -p testpr -E -v file:/dev/null
```
Then I used this command to create the print jobs (Here I printed a pdf named Sample).
```
lp -d testpr Sample.pdf
```
