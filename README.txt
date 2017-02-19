
I wanted to play a variant called "checkless chess" where you can only check in the case of checkmate, but could find no engine support. I added the rule to this simple engine as a proof of concept. One major problem is that the user can make an illegal move while playing on a GUI (I'm using Arena)

///////////////////////////////////////////////////////////

-secondchess is a derivative of firstchess

-Its main aim is to add the neccesary code to firstchess in order
to make it play real chess, especially adding the rules for castle and en 
passant capture, focusing in an easy to read code.

-To compile under linux just "gcc secondchess.c -o secondchess -Ofast"

-To compile under windows try tcc, geany+gcc, lcc. More info on the topic on http://www.chess2u.com/t5750-secondchess

-Acknowledgments:
 -Pham Hong Nguyen, author of firstchess
 -Pedro Castro, author of danasah
 -The authors of http://chessprogramming.wikispaces.com/
 -Tony Mokonen for his windows compilations
 -Tom Kerrigan for TSCP
 -Bruce Moreland for his site
 -The people who post on talkchess
 -Jonatan Pettersson, author of mediocre chess
 -Graham Banks and Dusan Stamenkovic for their logos
 -Many more...

