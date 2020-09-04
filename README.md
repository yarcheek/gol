# Game of Life

PHP implementation of [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

## How to run application

```
php gol.php -i in.xml
```

You can decide on the output format if any - file, screen, etc. For us is more important the business logic behind it. This is not a test of your web coding (HTLM, CSS, JS, etc) skills. It's about your PHP craft.

## Sample input

```xml
<?xml version="1.0"?>
<life>
    <world>
        <cells>4</cells> <!-- Dimension of the square "world" -->
        <species>1</species> <!-- Number of distinct species -->
        <iterations>10</iterations> <!-- Number of iterations to be calculated -->
    </world>
    <organisms>
        <organism>
            <x_pos>2</x_pos> <!-- x position -->
            <y_pos>0</y_pos> <!-- y position -->
            <species>0</species> <!-- Species type -->
        </organism>
        <organism>
            <x_pos>0</x_pos>
            <y_pos>1</y_pos>
            <species>0</species>
        </organism>
        <organism>
            <x_pos>3</x_pos>
            <y_pos>1</y_pos>
            <species>0</species>
        </organism>
        <organism>
            <x_pos>0</x_pos>
            <y_pos>2</y_pos>
            <species>0</species>
        </organism>
        <organism>
            <x_pos>3</x_pos>
            <y_pos>2</y_pos>
            <species>0</species>
        </organism>
        <organism>
            <x_pos>1</x_pos>
            <y_pos>3</y_pos>
            <species>0</species>
        </organism>
    </organisms>
</life>
```
