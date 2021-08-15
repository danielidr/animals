# README

Github: https://github.com/danielidr/animals

Para este proyecto se puede implementar polimorfismo para poder asignar el tipo de animal o especie por la columna animalable type, donde en el modelo animal se relaciona con el resto de los modelos que son cat, dog y cow, como se muestra en el diagrama.

![GitHub Logo](/app/assets/images/diagram.jpg)

Para relacionarlo se deberá crear primero el animal:

```ruby
dog = Dog.create
```

Luego se debe crear el animal:

```ruby
animal = Animal.new
```

Para despúes asigarle el tipo de animal a la tabla animal:

```ruby
dog.animals << animal
```

Donde se creará finalmente el animal.