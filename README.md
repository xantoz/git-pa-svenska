# Git på svenska

## Introduktion

Det dagliga språket för de olika kommandona i `git` (eller `jävel`) är
på svenska ett enda stort svengelskakalas. Jag finner mig själv ofta
sägandes _"Kan du pusha branchen?"_ eller _"Jag pullar!"_, vilket
känns pinsamt.

Detta dokument ämnar etablera en ren svensk jargong som kan användas
på arbetsplatsen för att med fördel undvika pressade situationer med
kollegor samt boskap.

## Förslag

Nedan följer tabeller över verb och substantiv relaterade till git,
deras nuvarande bruk samt förslag på hur vi tillsammans kan bättra
oss.

| Verb        | Nuvarande bruk | Förslag                                      |
|-------------|----------------|----------------------------------------------|
| pull        | pulla          | dra in, indrag                               |
| push        | pusha          | lägga upp                                    |
| fetch       | fetcha         | hämta                                        |
| branch      | brancha        | förgrena                                     |
| commit      | commita        | sätta in, insätta                            |
| rebase      | rebasa         | ympa                                         |
| merge       | merga          | sammanfoga                                   |
| squash      | squasha        | mosa                                         |
| stash       | stasha         | gömma                                        |
| tag         | tagga          | etikettera, sätta etikett, skapa etikett     |
| cherry-pick | cherry-picka   | plocka russin, russinplocka                  |
| amend       | amenda         | rätta till                                   |
| blame       | blamea         | klandra                                      |

| Substantiv   | Nuvarande bruk | Förslag           |
|--------------|----------------|----------------   |
| git          | git            | tölp              |
| repository   | repo           | ett förvar        |
| branch       | branch         | en gren           |
| commit       | commit         | en insättning     |
| pull request | pull request   | en indragsbegäran |
| stash        | stash          | en gömma          |
| tag          | tagg           | en etikett        |

## Exempel

    - Kan du rycka grenen jag just ympade och knuffa till github?

    - Jag förgrenade alldeles nyss och förband ändringarna från min gömma där.

    - Skicka en ryckbegäran när du är färdig med sammanfogningen!

    - Låt oss plocka russin från mäster-grenen.
    
    - Hoppsan, jag råkade visst kraftknuffa mot mäster-grenen.. D:

    - Mosa dina förbindelser innan du sammanfogar.

## Dagligt bruk

Nedan följer en rad kommandoradskommandon för att sätta upp en svensk
gitmiljö. Avsaknaden av svenska tecken i täcknamnen beror på en brist i git
(överväg att förbättra mjukvaran och skicka en ryckbegäran!). Följande
kommandon ändrar din `~/.gitconfig` och kommer att verka globalt.

    git config --global alias.ryck pull
    git config --global alias.knuffa push
    git config --global alias.gren branch
    git config --global alias.forgrena branch
    git config --global alias.forbinda commit
    git config --global alias.ympa rebase
    git config --global alias.sammanfoga merge
    git config --global alias.gom stash
    git config --global alias.klandra blame
    git config --global alias.marke tag
    git config --global alias.mark tag

    alias jävel=git
