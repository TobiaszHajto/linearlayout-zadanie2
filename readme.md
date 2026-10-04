1.Ile poziomów zagnieżdżenia ma mój układ i jak to policzyłem?

Układ ma 3 poziomy zagnieżdżenia LinearLayout. Liczę je od głównego LinearLayout, przez kolejne LinearLayouty, aż do tego, w którym są przyciski. TextView i Button nie są LinearLayoutami, więc ich nie liczę.

2.Jakie wagi mają przyciski w ostatnim rzędzie i dlaczego?

Przyciski `0` i `,` mają wagę 1, a przycisk `=` ma wagę 2. Dzięki temu `=` jest dwa razy szerszy od `0` i `,`. Szerokość przycisków jest ustawiana przez wagi, a nie przez stałą wartość dp.
