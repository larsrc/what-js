what-js
=======

A (mainly) debugging library in an eloquent style.

```
function(foo, bar) {
  if (foo == bar) {
    what.happenedHere("Should never have foo ", foo, " equal bar ", bar);
  }
  if (bar == 0) {
    what.theFuck("I _know_ I checked for bar == 0 before calling.");
  }
  switch (foo) {
    case 1: return 'this';
    case 2: return 'that';
    default: what.toDo("When foo is neither 1 nor 2, but ", foo);
  }
}
