# Liquid Widont

A Liquid Filter that prevents widows on texts by replacing the space between the last two words with a non-breaking space.

Allows you to turn this:  

```
You have to see it to believe  
it                            
```

into this:  

```
You have to see it to  
believe it
```

## Usage

```{{ post.title | widont }}```

## Contributors

- Daniel da Silva - @danielfdsilva
- Olaf Veerman - @obirdman


