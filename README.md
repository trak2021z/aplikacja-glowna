# aplikacja-glowna


### Pobranie całej aplikacji:
``` git clone --recursive https://github.com/aplikacje-internetowe-l2/aplikacja-glowna.git ```

### Wejście do folderu:
``` cd aplikacja-glowna ```

### Uruchomienie aplikacji:
``` docker-compose up -d --build```
parametry sprawiają że aplikacja będzie postawiona od zera i nie będzie wykorzystywać starych komponentów

### Posprzątanie 
```docker-compose down -v --rmi all --remove-orphans```


### Korzystanie z aplikacji:
Należy wejść na adres http://127.0.0.1:8081/register
oraz wprowadzić dane logowania, hasło musi zawierać 8 znaków, małą i dużą literę, cyfrę oraz znak specjalny.

