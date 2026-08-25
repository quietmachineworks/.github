## Quiet Machine Works

[English](#english) | [Français](#français)

### English

Small, sharp tools for people who ship alone.

A rule nobody enforces is an intention. A check that needs supervision is one
more thing to maintain. What survives a solo workload is the mechanism that
holds on its own, costs nothing on the day it is adopted, and explains itself
to whoever trips it six months later.

Everything here follows the same shape:

- **One thing.** A tool that does two is two tools sharing a bug tracker.
- **Adoptable today.** On the real codebase, in its current state, without a
  cleanup project first. A tool that requires a clean slate never gets used.
- **It teaches when it fails.** A message that says "not allowed" gets worked
  around. One that says what broke gets remembered.
- **Opinionated, and honest about it.** These encode one way of working. The
  mechanism travels; the taste stays here.

Built while shipping real projects, not as a side quest.

#### The tools

One plugin, one install, everything in it:

```
/plugin marketplace add quietmachineworks/qmw
/plugin install qmw@quietmachineworks
```

- **`/qmw:ratchet-audit`** - report which of a project's stated code rules are
  enforced, and which could be. Writes nothing.
- **`/qmw:ratchet-add`** - build the check that enforces one, frozen at today's
  count so a repository that already breaks the rule can adopt it today.
- **`/qmw:survey`** - audit the whole codebase, or one perimeter of it, the way
  a vessel gets surveyed before purchase: a prioritized defect list, judged
  against the stack the project actually runs. Fixes nothing, writes nothing.
- **`/qmw:shakedown`** - play a real user through a product's UI, screen by
  screen, on a genuinely empty environment, until every screen in scope survives
  contact with reality.
- **`/qmw:squawk`** - run one reported bug from incident to proven fix:
  reproduced in a real browser before any code changes, fixed at the class
  rather than the symptom, then proven the way it was found.

It all lives in **[quietmachineworks/qmw](https://github.com/quietmachineworks/qmw)**.

---

### Français

Des outils courts et tranchants, pour ceux qui livrent seuls.

Une règle que personne n'applique est une intention. Un contrôle qui demande à
être surveillé est une chose de plus à maintenir. Ce qui survit à une charge de
travail solo, c'est le mécanisme qui tient tout seul, ne coûte rien le jour où
on l'adopte, et s'explique de lui-même à celui qui le déclenchera six mois plus
tard.

Tout ici a la même forme :

- **Une seule chose.** Un outil qui en fait deux, c'est deux outils qui
  partagent un gestionnaire de bugs.
- **Adoptable aujourd'hui.** Sur le vrai code, dans son état actuel, sans
  chantier de nettoyage préalable. Un outil qui exige une page blanche ne sert
  jamais.
- **Il enseigne quand il échoue.** Un message qui dit « interdit » se
  contourne. Un message qui dit ce qui a cassé se retient.
- **Assumé, et honnête là-dessus.** Ces outils encodent une façon de
  travailler. Le mécanisme voyage ; le goût reste ici.

Écrits en livrant de vrais projets, pas comme une quête secondaire.

#### Les outils

Un plugin, une installation, tout dedans :

```
/plugin marketplace add quietmachineworks/qmw
/plugin install qmw@quietmachineworks
```

- **`/qmw:ratchet-audit`** - dit lesquelles des règles de code qu'un projet
  s'est données sont réellement appliquées, et lesquelles pourraient l'être.
  N'écrit rien.
- **`/qmw:ratchet-add`** - construit le contrôle qui applique l'une d'elles, gelé
  au compte du jour, pour qu'un dépôt qui enfreint déjà la règle puisse l'adopter
  aujourd'hui.
- **`/qmw:survey`** - audite la totalité du code, ou un seul périmètre, comme on
  expertise un navire avant l'achat : une liste de défauts priorisée, jugée
  contre la stack que le projet fait réellement tourner. Ne corrige rien,
  n'écrit rien.
- **`/qmw:shakedown`** - joue un vrai utilisateur dans l'interface d'un produit,
  écran par écran, sur un environnement réellement vide, jusqu'à ce que chaque
  écran du périmètre survive au contact du réel.
- **`/qmw:squawk`** - mène un bug signalé de l'incident au fix prouvé :
  reproduit dans un vrai navigateur avant de toucher au code, corrigé à la
  classe plutôt qu'au symptôme, puis prouvé comme il a été trouvé.

Le tout vit dans **[quietmachineworks/qmw](https://github.com/quietmachineworks/qmw)**.
