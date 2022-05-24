| Ge                                                                                 | En                                                                                |
|------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| 🔴dieses **Licht** ist `wirklich hell` und überhaupt nicht `dunkel`                | This **light** is `really bright` and not dark at `all`                           |
| 🔴dieser **Tisch** ist `praktisch`, weil er `breit` und nicht `schmall` ist        | This **table** is `practical` because it is `wide` and not `narrow`               |
| 🔴dieser **Sessel** ist `unpraktisch`, weil er `altmodisch` und nicht `modern` ist | This **armchair** is `impractical` Because it is `old-fashioned` and not `modern` |
| 🔴dieser **Teppich** ist überhaupt nicht `billig`/`günstig`, sondern eher `teuer`  | This **carpet** is not `cheap` at all, but rather `expensive`                     |
| 🔴dieser **Schrank** ist nicht `klein`, sondern ziemlich `groß`                    | This **cupboard** is not small but rather big                                     |
| 🔴diese **Kommode** ist nicht `lang` und nicht `kurz` sie hat eine `normale` Größe | That **commode** is not `long` and not `short` It has a `normal` size             |
| 🔴die Nacht ist dunkel und der Tag ist hell                                        | The **night** is `dark` and the day is `bright`                                   |
| Besser neu als alt                                                                 | Better new than old                                                               |
| Es ist `leicht` zu lesen, aber `schwer` zu merken                                  | It is `easy` to read but `difficult` to remember                                  |
| Es ist `leicht`, sich dieses **Bild** vorzustellen, obwohl es `schwer`             | It is `easy` to imagine this **picture** though it is `difficult` to draw it      |
| /`schwierig` ist, es zu zeichnen                                                   |                                                                                   |
| Dein **Fenster** ist `schön` und nicht so `hässlich` wie meines                    | Your **window** is `beautiful` and not `ugly` as mine                             |


**RegExp to extract from table (1st column):** `^\|(.*)\|`
1. This **light** is `really bright` and not dark at `all`
2. This **table** is `practical` because it is `wide` and not `narrow`
3. This **armchair** is `impractical` Because it is `old-fashioned` and not `modern`.
4. This **carpet** is not `cheap` at all, but rather `expensive`
5. This **cupboard** is not small but rather big.
6. That **commode** is not `long` and not `short`. It has a `normal` size.
7. The **night** is `dark` and the day is `bright`.
8. Better new than old.
9. It is `easy` to read but `difficult` to remember.
10. It is `easy` to imagine this picture though it is `difficult` to draw it.
11. Your **window** is `beautiful` and not `ugly` as mine.


1. Dieses **Licht** ist `wirklich hell` und überhaupt nicht `dunkel`
2. Dieser **Tisch** ist `praktisch`, weil er `breit` und nicht `schmall` ist
3. Dieser **Sessel** ist `unpraktisch`, weil er `altmodisch` und nicht `modern` ist.
4. Dieser **Teppich** ist überhaupt nicht `billig`/`günstig`, sondern eher `teuer`
5. Dieser **Schrank** ist nicht `klein`, sondern ziemlich `groß`.
6. Diese **Kommode** ist nicht `lang` und nicht `kurz`. Sie hat eine `normale` Größe.
7. Die Nacht ist dunkel und der Tag ist hell.
8. Besser neu als alt
9. Es ist `leicht` zu lesen, aber `schwer` zu merken.
10. Es ist `leicht`, sich dieses Bild vorzustellen, obwohl es `*schwer`/`schwierig` ist, es zu zeichnen.
11. Dein **Fenster** ist `schön` und nicht so `hässlich` wie meines.

