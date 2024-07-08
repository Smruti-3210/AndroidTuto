# AndroidTuto

## Preview of My Application

### Final Appearance of My Application

![Screenshot](Application1/ss-7.png)

### Details about Jetpack Compose Composables Used

#### Row
The `Row` composable is used to arrange its children in a horizontal sequence. It allows you to align items horizontally and customize their arrangement.

```kotlin
Row(
    modifier = Modifier.fillMaxWidth(),
    horizontalArrangement = Arrangement.SpaceBetween
) {
    Text(text = "Item 1")
    Text(text = "Item 2")
    Text(text = "Item 3")
}
