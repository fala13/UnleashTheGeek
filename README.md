CLI referee for UnleashTheGeek game (https://github.com/fala13/UnleashTheGeek) aimed to work with Brutaltester (https://github.com/dreignier/cg-brutaltester)

# Compiled
Just check https://github.com/fala13/UnleashTheGeek/releases

# To compile
mvn package

# Example use
java -jar target/unleash-the-geek-2019-gold-1.0-SNAPSHOT.jar -p1 "python3 -u ../bronze171.py" -p2 "python3 -u ../brone564.py" -l gamelog1.json

Where "python3 -u ../bronze171.py" is the player program process.

With cg-brutaltester:
java -jar cg-brutaltester/target/cg-brutaltester-1.0.0-SNAPSHOT.jar -r "java -jar UnleashTheGeek/target/unleash-the-geek-2019-gold-1.0-SNAPSHOT.jar" -p1 "python3 -u unleash.py" -p2 "python3 -u bronze171.py" -t 1 -n 10 -l "./logs/" -v

Contest Unleash The Geek https://www.codingame.com/contests/unleash-the-geek-amadeus
