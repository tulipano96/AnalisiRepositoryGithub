# AnalisiRepositoryGithub
Analisi delle repositories più popolari sulla piattaforma di GitHub al fine di comprendere quali sono i trend attuali e i futuri sviluppi dell'Open Source Software.

La seguente Web-App utilizza le GitHub Search API per effettuare le analisi. Tuttavia, tali API sono sottoposte a delle limitazioni sul numero di richieste effettuabili. Per aggirare tali limitazioni, c'è bisogno di autenticarsi utilizzando il Nome Utente del proprio account GitHub e il Personal Access Token, generato automaticamente nella sezione dedicata.

N.B: 

1)Per il corretto funzionamento della web-app bisogna modificare le variabili d'istanza "username" (Nome utente GitHub) e "accessTkn" (Personal Access Token) nella classe java "RequestGenerator", nel package src/newCore.

2)Inoltre, per analisi approfondite che superano i limiti imposti dalle Search API di GitHub, bisogna inserire, nel costruttore della classe RequestGenerator, "usernameArray[0]" e "usernameArray[1]", con i relativi "githubTokenArray[1]" e "githubTokenArray[2]".
Questi parametri inseriti sono ausiliari e utili nel caso in cui l'account primario raggiunga il limite di richieste effettuabili tramite Search API.
