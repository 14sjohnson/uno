<template class="Scroll">

    <div class="Scroll">
        <v-container>
            <section id="rules">
                
                <h2> Rules: </h2>
                <a id=section1><p class=text ><br>The first player is normally the player to the left of the dealer (you can also choose the youngest player) and gameplay usually follows a clockwise direction. Every player views his/her cards and tries to match the card in the Discard Pile.
                    You have to match either by the number, color, or the symbol/Action. For instance, if the Discard Pile has a red card that is an 8 you have to place either a red card or a card with an 8 on it. You can also play a Wild card (which can alter current color in play).<br>
                    <br>If the player has no matches or they choose not to play any of their cards even though they might have a match, they must draw a card from the Draw pile. If that card can be played, play it. Otherwise, keep the card, and the game moves on to the next person in turn. You can also play a Wild card, or a Wild Draw Four card on your turn.<br>
                    <br>Note: If the first card turned up from the Draw Pile (to form the Discard Pile) is an Action card, the Action from that card applies and must be carried out by the first player to go (as stated, it is usually the player to the dealer’s left). The exceptions are if a Wild or Wild Draw Four card is turned up.
                    If it is a Wild card, the first player to start (usually the one on the dealer’s left), can choose whatever color to begin play. If the first card is a Wild Draw Four card – Return it to the Draw Pile, shuffle the deck, and turn over a new card.<br>
                    <br>Take note that you can only put down one card at a time; you cannot stack two or more cards together on the same turn. For example, you cannot put down a Draw Two on top of another Draw Two, or Wild Draw Four during the same turn, or put down two Wild Draw Four cards together.<br>
                    <br>The game continues until a player has one card left. The moment a player has just one card they must yell “UNO!”. If they are caught not saying “Uno” by another player before the next player has taken their turn, that player must draw two new cards as a penalty. Assuming that the player is unable to play/discard their last card and needs to draw, but after drawing, is then able to play/discard that penultimate card, the player has to repeat the action of calling out “Uno”. The bottom line is – Announcing “Uno” needs to be repeated every time you are left with one card.
                    Once a player has no cards remaining, the game round is over, points are scored, and the game begins over again. Normally, everyone tries to be the first one to achieve 500 points, but you can also choose whatever points number to win the game, as long as everyone agrees to it.<br>
                </p></a>
            </section>    
            <section id="tutorials"> 
                              
                <h2> Tutorials: </h2>
                <a id="section2"><p class=text > Tutorials here</p></a>
            </section>    
            <section id="cardAbilities">
                
                <h2> Card Abilities: </h2>
            
                <a id="section3"><p class=text  ><br><strong>Action Cards:</strong>  Besides the number cards, there are several other cards that help mix up the game. These are called Action or Symbol cards.<br>

                    <br><strong>Uno Action Cards</strong><br>

                    <Card :number="1" :color="'red'"></Card><br><br>
                    <strong> Reverse </strong> – If going clockwise, switch to counterclockwise or vice versa. It can only be played on a card that matches by color, or on another Reverse card. If turned up at the beginning of play, the dealer goes first, and the player to the dealer’s right is next (normally it would be the player to the dealer’s left).<br><br><br><br><br>
                    <Card :number="1" :color="'red'"></Card><br><br>
                    <strong> Skip </strong> – When a player places this card, the next player has to skip their turn. It can only be played on a card that matches by color, or on another Skip card. If turned up at the beginning of play, the first player (to the dealer’s left) loses his/her turn. The next player to that player’s right starts the game instead.<br><br><br><br><br>
                    <Card :number="1" :color="'red'"></Card><br><br><br>
                    <strong> Draw Two </strong> – When a person places this card, the next player will have to pick up two cards and forfeit his/her turn. It can only be played on a card that matches by color, or on another Draw Two. If turned up at the beginning of play, the first player draws two cards and gets skipped.<br><br><br><br><br>
                    <Card :number="1" :color="'red'"></Card><br><br>
                    <strong> Wild </strong> – This card represents all four colors, and can be placed on any card. The player has to state which color it will represent for the next player. It can be played regardless of whether another card is available. If turned up at the beginning of play, the first player chooses what color to continue play.<br><br><br><br><br>
                    <Card :number="1" :color="'red'"></Card><br><br>
                    <strong> Wild Draw Four </strong> – This acts just like the wild card except that the next player also has to draw four cards as well as forfeit his/her turn. With this card, you must have no other alternative cards to play that matches the color of the card previously played. If you play this card illegally, you may be challenged by the other player to show your hand to him/her. If guilty, you need to draw 4 cards. If not, the challenger needs to draw 6 cards instead. If turned up at the beginning of play, return this card to the Draw pile, shuffle, and turn up a new one.<br><br><br><br><br>
                    <Card :number="1" :color="'red'"></Card><br>
                    <strong> Wild Swap Hands Card </strong> – This is a powerful card that enables you to swap the cards in your hand with anyone of your choice. Being a Wild card, it has the same attributes, namely, you can choose to either play it or not, at any of your turns, and also choose the color of play. Ideally, you would probably want to swap your cards with the player who has the least number of cards! Being a powerful Action card, only one is provided per deck. If turned up at the beginning of the game, the first player to start gets to choose the color and also swap his hands with another person. Note: Being a Wild card, the same rule applies to the Swap Hands card. Once you play this card and swapped your hands with another player, your turn is up, and you are not allowed to put down any card immediately after that until your turn arrives again.<br><br><br><br><br>
                    <Card :number="1" :color="'red'"></Card><br>
                    <strong> Wild Customizable Card </strong> – There are 3 of them provided in any deck, and they are all blank. These are meant for you to write down your own “house rules”. Before the game starts, make sure everyone agrees to the rules and also on how many of the Wild Customizable cards will be used. You can use 1-3 of them per game. These are Wild Cards, so the same rules apply to them – The person who plays them gets to choose the color of play, and if turned up at the start, then the first player chooses the color of play. Note: Being a Wild card, the same rule applies to the Customizable card. Once you play this card, your turn is up, and you are not allowed to put down any card immediately after that until your turn arrives again.<br>
                    
                </p></a>
            </section>
        </v-container>
    </div>        
</template>
<style>
@import url(https://fonts.googleapis.com/css?family=Source+Sans+Pro:900);
    /* .rules{
        background-color: black;
    } */
    .Scroll{
        height:100%;
        overflow:scroll; 
        overflow-block: black;
    }
    .text{
        /* display: show; */
        /* position: absolute; */
        color:#ddd;
        display: inline;
        display: block;
        /* min-width: 160px; */
        }
</style>

<script>
 import Card from "../components/Card";
 export default {
    components: {
    Card
  },
 }
</script>
