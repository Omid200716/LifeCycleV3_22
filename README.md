MainActivity, HomeActivity, ProfileActivity, och RegisterActivity. Här är en kort beskrivning av varje aktivitet:

    MainActivity: Detta är inloggningsaktiviteten där användaren anger användarnamn och lösenord. Om inloggningen lyckas, omdirigeras användaren till HomeActivity. Om användaren trycker på "Registrera" knappen, skickas de till RegisterActivity.

    HomeActivity: Detta är huvudaktiviteten där användaren hamnar efter inloggning. Den har en bottennavigeringsmeny för att navigera mellan olika delar av appen, inklusive användarprofilen och registreringssidan.

    ProfileActivity: Detta är användarprofilaktiviteten som visar användarens information, inklusive namn, lösenord, e-post, ålder och om de har körkort. Användaren kan också navigera till andra delar av appen via bottenmenyn.

    RegisterActivity: Denna aktivitet används för att registrera en ny användare eller uppdatera befintlig användarinformation. Den låter användaren ange sitt namn, lösenord, ålder, e-post och om de har ett körkort. Registrerad information sparas i delade preferenser och användaren kan sedan omdirigeras till sin profil.
