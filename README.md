# AnalisiRepositoryGithub
Analisi delle repositories più popolari sulla piattaforma di GitHub al fine di comprendere quali sono i trend attuali e i futuri sviluppi dell'Open Source Software.

N.B: 

1)Per il corretto funzionamento della web-app bisogna modificare le variabili d'istanza "username" (Nome utente GitHub) e "accessTkn" nella classe java "RequestGenerator", nel package src/newCore.

2)Inoltre, per analisi approfondite che superano i limiti imposti dalle Search API di GitHub, bisogna inserire, nel costruttore della classe RequestGenerator, "usernameArray[0]" e "usernameArray[1]", con i relativi "githubTokenArray[1]" e "githubTokenArray[2]".
Questi parametri inseriti sono ausiliari e utili nel caso in cui l'account primario raggiunga il limite di richieste effettuabili tramite Search API.
