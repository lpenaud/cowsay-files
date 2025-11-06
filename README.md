# Cowsay files
My personal cowsay files.

## How to use

* Add to your `COWPATH`
* Or use the flag `-f`

## Example

Call `cowsay` with the file [doctor-who-the-fourth.cow](cows/doctor-who-the-fourth.cow) and write the output to your clipboard instead of standard output, so you can paste the art wherever you want.

```bash
printf "%s\n" "First line" "Second one" \
  | cowsay -n -f cows/doctor-who-the-fourth.cow \
  | xclip -selection clipboard -in
```
