## Header

# Header
## Header 2
### Header 3
#### Header 4
...

---
## Screenshots

![[Pasted image 20230124100340.png]]
1. Screenshot saved to clipboard
2. `cmd + v` in Document
	1. Automatically adds image to attatchments
	2. Creates a Link to the attatchment

---

## Code

```dart
"this is a code section"
class Example extends StatelessWidget {
  const Example({super.key});

  @override
  Widget build(BuildContext context) {
    return Container();
  }
}
```
- Keep Formatting
	- Right-click  `Paste as plain Text`

Code can be `copied` by clicking on the `Language descriptor`  at the top right

---

## Lists

- unordered
	- subnote
		- asd
	- asd
- asd


1. ordered
	1. subnote
		1. asd
	2. asd
2. asd

Start with a  `-[space]` 
`Enter` adds a note on the same level
`Tab` moves to the sublevel
`Shift + Tab` moves to the higher level
End with 2x `Enter`

They can be mixed

---

## Links

[[Example]]
[[Example#Header]]

- Start with `[[`
- Add the name of the `file` to link to
- Add a `#` and the name of the `section` 
	- The section must already exitst

---

## Embeddings

![[Example#Test]]

- Create a [[#Links]] to the `file` or `section` you want to embed
- Add a `!` infront of the link

This is still a Link and can be accessed via the symbol at the top right

---

## Tables

Column 1 | Column 2 | Column 3
-|:-:|-:
content|asd|asd

1. Start by writing down your `column headers` divided by `|`
2. Add a line that consists of `-` in place of the column content and the same `|` as above
	- This should look somewhat like `-|-|-|-`
	2. You can add `:` to the left, right or both sides of a `-` to align the content of that column
1. Add your content in the following lined
	- Devided into rows by `|`

