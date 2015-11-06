## Arrays of Objects

1. Write a function that logs everything in an array.

```
var list = ['milk', 'butter', 'cheese'];

logList([ist);
// =>  milk
// =>  butter
// =>  cheese
```

1. Write a function that logs the first and last item in an array.
```
var list = ['milk', 'butter', 'cheese'];

logFirstAndLast(list);
// =>  milk
// =>  cheese
```


1. Write a function that returns each string in this array in all uppercase letters.

Example:

```
var list = ['red', 'green', 'blue'];

toUpperCase([list]);
// => ['RED', 'GREEN', 'BLUE'];

```
1. Write a function that returns each string in this array in all lowercase letters.

Example:

```
var list = ['RED', 'GREEN', 'BLUE'];

toLowerCase([list]);
// => ['red', 'green', 'blue'];

```

2. Write a function that accepts an array of objects and logs the color attribute of each.

Example:

```
var list = [
  {width: 20, color: 'red'},
  {width: 50, color: 'blue'},
  {width: 10, color: 'purple'}
];

getColors(list);
// => 'red'
// => 'blue'
// => 'purple'
```



3. Write a function that logs the object with the greatest strength attribute.

Example:

```
var orcs = [
	{name: 'Orgoth', strength: 9001},
	{name: 'Blaroguhh', strength: 500},
	{name: 'Mark', strength: 543}
]
getStrongest(orcs);
// => {name: 'Orgoth', strength: 9001}

```



4. Write a function that logs the object with the lowest strength attrubute.

Example:

```
var orcs = [
	{name: 'Orgoth', strength: 9001},
	{name: 'Blaroguhh', strength: 500},
	{name: 'Mark', strength: 543}
]
getWeakest(orcs);
// => {name: 'Blaroguhh', strength: 500}

```

5. Write a function that lists the weapons for the Strongest Orc.

Example:

```
var orcs = [
	{
		name: 'Orgoth',
		strength: 9001,
		weapons: ['Bone ax', 'Mace of Strength']
	},
	{
		name: 'Blaroguhh',
		strength: 500,
		weapons: ['Cheeseburger', 'Spear of the Hut']
	},
	{
		name: 'Mark',
		strength: 543,
		weapons: ['Ax of Defense', 'Dagger', 'Sword' ]
	}
]
getStrongestWeapons(orcs);
// => 	['Bone ax', 'Mace of Strength']

```

5. Write a function that lists the Orc that has the most the weapons.

Example:

```
var orcs = [
	{
		name: 'Orgoth',
		strength: 9001,
		weapons: ['Bone ax', 'Mace of Strength']
	},
	{
		name: 'Blaroguhh',
		strength: 500,
		weapons: ['Cheeseburger', 'Spear of the Hut']
	},
	{
		name: 'Mark',
		strength: 543,
		weapons: ['Ax of Defense', 'Dagger', 'Sword']
	},
	{
		name: 'Mace',
		strength: 888,
		weapons: ['Ax of Defense', 'Dagger', 'Sword']
	}
]
getMostWeapons(orcs);
// => 	[{name: 'Mark', strength: 543, weapons: ['Ax of Defense', 'Dagger', 'Sword' ]}, {name: "Mace", strength: 888, weapons: ["Ax of Defense", "Dagger", "Sword"]}]

```

