## Base Karel commnds:
---

move()
turn_left()
put_beeper()
pick_beeper()


## Names of the conditions:
---

| Test | Opposite | Checks |
| -------- | -------- | --------- |
| front_is_clear() | front_is_blocked() | Is there a wall in front of Karel? |
| beepers_present() | no_beepers_present() | Are there beepers on this corner? |
| left_is_clear() | left_is_blocked() | Is there a wall to Karel’s left? |
| right_is_clear() | right_is_blocked() | Is there a wall to Karel’s right? |
| beepers_in_bag() | no_beepers_in_bag() | Does Karel have any beepers in its bag? |
| facing_north() | not_facing_north() | Is Karel facing north? |
| facing_south() | not_facing_south() | Is Karel facing south? |
| facing_east() | not_facing_east() | Is Karel facing east? |
| facing_west() | not_facing_west() | Is Karel facing west? |


## Conditions:
---

```python
if condition:
    code run if condition passes

if condition:
    code block for "yes"
else:
    code block for "no"
```

## Loops:
---

```python
for i in range( count):
    code to repeat

while condition:
    code to repeat
```

## Function Declaration:
---

```python
def name():
    code in the body of the function.
```

## Extra Karel Commands:
---

paint_corner(COLOR_NAME)
corner_color_is(COLOR_NAME)

### Color names :
---

- BLANK, which removes any color on the square
- BLACK
- BLUE
- CYAN
- DARK_GRAY
- GRAY
- GREEN
- LIGHT_GRAY
- MAGENTA
- ORANGE
- PINK
- RED
- WHITE
- YELLOW