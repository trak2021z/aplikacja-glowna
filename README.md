# aplikacja-glowna


### Pobranie całej aplikacji:
``` git clone https://github.com/aplikacje-internetowe-l2/aplikacja-glowna.git ```

### Wejście do folderu:
``` cd aplikacja-glowna ```

### Uruchomienie aplikacji:
``` docker stack deploy -c docker-compose.yaml app_glowna ```


### Posprzątanie 
```docker stack rm app_glowna```


### Korzystanie z aplikacji:
Należy wejść na adres http://127.0.0.1:8081/register
oraz wprowadzić dane logowania, hasło musi zawierać 8 znaków, małą i dużą literę, cyfrę oraz znak specjalny.

