---
switcher-label: 选择器
---

# Topic title

## Section One {switcher-key="悬旗"}

The content that should appear when the Section Once is selected.

## Section Two {switcher-key="haha"}

The content that should appear when the Section Two is selected.

## Chapter's title {collapsible="true"}

Some content.

## Code block

```kotlin
    class Person(val name: String) {
        val children: MutableList<Person> = mutableListOf()

        constructor(name: String, parent: Person) : this(name) {
            parent.children.add(this)
        }
    }
```

{collapsible="true" collapsed-title="Person.kt"}

## Definition list

{collapsible="true"}
Expanded by default
{collapsible="true" default-state="expanded"}
: This is the definition of the first term.

Collapsed by default
{collapsible="true" default-state="collapsed"}
: This is the definition of the second term.

## Tip

> A piece of advice

## Note

> Just FYI.
> {style="note"}

## 视频

<video src="https://youtu.be/BeJu9bMPLGU"/>

## 列表

1. First item.
    1. First indented item.
    2. Second indented item.
       {style=“alpha-lower”}
2. Second item.
3. Third item
4. Fourth item

- Some list item
- Another list item
- Yet another list item
    - Some indented item
    - Another indented item
- One more item

## Definition

{style="full" sorted="desc" }
First Term
: This is the definition of the first term.

Second Term
: This is the definition of the second term.

Second Term
: This is the definition of the second term.

## Tables

| Foo    | Bar    | Baz      |
|--------|--------|----------|
| One    | Two    | Three    |
| Higher | Faster | Stronger |

## Tab

<tabs>
    <tab title="Vue">
        Hello Vue!
    </tab>
    <tab title="React">
        Hello React!
    </tab>
</tabs>

## Code block 代码块 {id="code-block_1"}

```
a code snippet
```

To output a line on the screen use
`echo "Hello world!"`.