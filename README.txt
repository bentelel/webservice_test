letzter stand der dinge:
watchtower watcht und bemerkt changes in image aber kann nicht builden >> authorization probleme.

github actions builden das docker image neu nach jedem push zu master > das passt


reverse proxy via traefik habe ich nicht ganz hingekriegt und ohne kann ich auch nicht 3 instancen des webservices hochspinnen, da nur ein port genutzt wird und ich den reverse proxy als loadbalancer brauche dazwischen.


also to do:

1) watchtower zum laufen kriegen
2) traefik als reverse proxy sauber einsetzen.
3) alles weitere > rumspielen mit main.go etc.
