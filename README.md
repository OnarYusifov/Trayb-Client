# Trayb - Client

Trayb is your all-in-one solution for an amazing looking Valorant Tournament Overlay, enabling all Organizers to display information like held gun, available credits etc. with just a single spectator running software.
To learn more and see a live demo, visit [trayb.az](https://www.trayb.az/).

It is comprised of three parts:
 - [The Trayb Client](https://github.com/Trayb/Trayb-Client)
   - Running this software on a single in-game observer provides the Trayb Server with all data currently provided by Overwolf.
 - [The Trayb Server](https://github.com/Trayb/Trayb-Server)
   - Ingests data from the Observer Client to reproduce the games state, allowing us to have an accurate representation of the game for further use.
 - [The Trayb Frontend](https://github.com/Trayb/Trayb-Frontend)
   - Receives the game state from the Server every 100 milliseconds, presenting it in a beautiful manner for viewers to enjoy.

Further updates for new features, as well as a detailed setup guide and an easy to host docker container are in the pipeline!

Trayb-Client isn't endorsed by Riot Games and doesn't reflect the views or opinions of Riot Games or anyone officially involved in producing or managing Riot Games properties. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
