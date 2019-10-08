CLI referee for UnleashTheGeek game (https://github.com/fala13/UnleashTheGeek) aimed to work with Brutaltester (https://github.com/dreignier/cg-brutaltester)

# Compiled
Just check https://github.com/fala13/UnleashTheGeek/releases

# To compile
mvn package

# Example use
java -jar -Dleague.level=4 target/unleash-the-geek-2019-gold-1.0-SNAPSHOT.jar -p1 "python3 -u ../bronze171.py" -p2 "python3 -u ../brone564.py" -l gamelog1.json

Where "python3 -u ../bronze171.py" is the player program process.

Contest Unleash The Geek https://www.codingame.com/contests/unleash-the-geek-amadeus
