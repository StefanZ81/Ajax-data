# Ajax-data

Openbare data-repo voor de J-Poule. Bevat ALLEEN openbare gegevens
(wedstrijdprogramma/stand, tv-zenders, nieuwsartikelen) en de workflows die
ze bijwerken. Hier staan geen persoonsgegevens, wachtwoorden of back-ups --
die blijven in de privé-repo met de code.

Workflows: `ajax-data-sync` (gestart door cron-job.org), `tv-zender-sync`,
`nieuws-sync`. Secret nodig: `FOOTBALL_DATA_API_KEY`.
