# Sumanasri Paila
### Basketball
**Raise the ring in victory! Bring On The Swish! One more attempt! Put the haters to rest!**

Everyone has their tastes and preferences.This statement applies for sports too."Basketball" is my favorite sport which I learned in my highschoo.The game was also invented in a college.I love this game because of its intensity where we do not have stops in the game and also the ball-handling skills.It also develops self-discipline and concentration.<br>**We will learn teamwork, although team work applies for every sport this game builds mutual trust and friendhip among team mates.**

-------
# Orderedlist
1. Basketball Federation of India.
2. Deepak Choudhary
3. Prashant Singh Rawat
4. Shashank Rai

# Unorderedlist
1. Washington Wizards
2. New York Knicks
3. Nuggets

------

[AboutMe](https://github.com/Sumanareddy13/assignment2-paila/commit/63f13f6760855473d2dcf68ece72499ae1e09010)

---------

# Countries I would recommend someone

Below table includes the information about the name of the country,reason why I would recommend someone to visit and number of days one could spend there.
| Name of Country  | Reason to visit          | No. of days |
|----------------- |----------------------    |------------ |
| Europe           |beautiful cities(Paris)   | 40          |
| India            |monuments,spiritual places| 30          |
| Switzerland      |mountains, scenic beauty  | 25          |
| Australia        |Infrastructure,Rainforests| 20          |

-----------
 >Truth hurts. Maybe not as much as jumping on a bicycle with a seat missing, but it hurts.***—Lt. Frank Drebin (Leslie Nielsen)***
 >A day without sunshine is like, you know, night.***—Steve Martin***

 -----------

# code fencing

>How to sort numbers?
(https://stackoverflow.com/questions/42303843/sorting-numbers-in-ascending-order)

~~~~~
@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}
~~~~~
(https://css-tricks.com/snippets/sass/sorting-function/)


