<p align="center">
  <img src="https://raw.githubusercontent.com/mkspcd/itw-contacts-list/master/images/banner.png" alt="Contacts banner" />
</p>

# Contacts List

Nous avons besoin de créer une fonction qui fusionne deux listes de contacts, venant de systèmes un peu différents. La fonction prend les deux listes de contact en entrée et nous retourne une seule liste.

- La fonction `mergeContacts` implémente la logique pour la fusion des deux listes, et retourne une unique liste.
- L'`id` du contact n'a pas d'importance et peut être changé. Il doit cependant être unique dans la liste retournée.
- Il est possible de proposer une solution qui modifie la structure des données retournées pour que cela soit plus pertinent.

```javascript
const contactsListA = {
  1: {
    firstName: 'Alice',
    phone: '0601020304',
  },
  3: {
    firstName: 'Bob',
    phone: '0711223344',
  },
  4: {
    firstName: 'Carole',
    phone: '0102030407',
  },
  5: {
    firstName: 'David',
    phone: '0102030408',
  },
}
```

```javascript
const contactsListB = {
  a: {
    firstName: 'Alice',
    phone: '0755512345',
    address: '350 Fifth Avenue New York',
  },
  b: {
    firstName: 'Bob',
    phone: '0711223344',
  },
  c: {
    firstName: 'Eve',
    phone: '0102030407',
    address: '221 B Baker Street',
  },
  d: {
    firstName: 'David',
    phone: '0102030408',
  },
  e: {
    firstName: 'Mallory',
    address: '1 Infinite Loop',
  },
}
```

```javascript
/**
 * Merge two contacts lists.
 * @param firstContactsList - The first list of contacts.
 * @param secondContactsList - The second list of contacts.
 * @returns - A list of merged contacts.
 */
function mergeContacts(firstContactsList, secondContactsList) {
  // TODO
}
```
