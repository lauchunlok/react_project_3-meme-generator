Design file: https://www.figma.com/file/MoLwFPHNHJVrzdFurxHzNV/Meme-Generator?node-id=0%3A1

### Mindset:

- All states are handled in `Meme`
- Every meme is an **object** that have 1. top text, 2. bottom text and 3. image
- 2 text inputs and 1 handleChange function
- useEffect to fetch API and update allMeme (state)
- getMemeImage to get random image and update the meme object(state)

### Learnt:

#### React:

1. State
2. useEffect & async
3. input

#### CSS:

1.  grid-template

```css
.form {
  display: grid;
  grid-template: 40px 40px / 1fr 1fr; /*  2 rows of 40px and then equally divide the column */
  gap: 17px;
  margin-bottom: 17px;
}

.form--button {
  grid-column: 1 / -1; /* from the beginning to the end */
  font-family: "Karla", sans-serif;
  border-radius: 5px;
  background: linear-gradient(90.41deg, #711f8d 1.14%, #a818da 100%);
  color: white;
  border: none;
  cursor: pointer;
}
```

2. Put Text in image
