## Contexte


En raison de la croissance massive des réseaux informatiques et des applications, de
nombreux défis se posent pour la recherche en cybersécurité. Les intrusions/attaques
peuvent être définies comme un ensemble d'événements capables de compromettre les
principes des systèmes informatiques, par exemple la disponibilité, l'autorité, la
confidentialité et l'intégrité. Pour répondre à ce besoin, le monde de la cybersécurité utilise
les technologies et connaissances d’autres domaines comme l’intelligence artificiel (IA) et
les graphes pour renforcer la sécurité des réseaux informatiques. A juste titre, la détection
d’intrusion réseau (IDS) peut se faire d’une manière supervisée ou non supervisée avec l’IA.
Notre travail à travers ce document consistera à la mise en place d’un IDS supervisé à partir
des données UNSW-NB15 Dataset récolté par IXIA PerfectStorm tool in the Cyber Range
Lab of UNSW Canberra.
Pour réaliser cela, nous construirons d’abord un graphe à partir des données du dataset.
Ensuite nous récupérons sa composante connexe la plus intéressante pour la suite de l’étude.
Nous générerons enfin de cette composante connexe des mesures que nous ajouterons à
notre dataset pour améliorer le modèle.
