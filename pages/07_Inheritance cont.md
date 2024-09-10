---
layout: center
---

# Inheritance (cont.)

<div class="grid grid-cols-2 gap-y-10 gap-x-2 mt-8">
<div class='flex-row'>

```mermaid
classDiagram
    Hewan <|-- Karnivora
    Hewan <|-- Herbivora
    Karnivora <|-- Harimau
    Karnivora <|-- Elang
    Herbivora <|-- Kambing
```

</div>
<div class='flex-row flex justify-center items-center'>
<div class='text-base text-justify mt-4'>

- Java hanya mengizinkan <span style="color: green; font-weight: bold;">single inheritance</span>, yakni subclass hanya dapat memiliki satu parent class.

- Satu parent class dapat memiliki <span style="color: green; font-weight: bold;">banyak</span> subclass yang disebut <span style="color: green; font-weight: bold;">hierarchical inheritance</span>.

- Satu subclass dapat memiliki subclass lagi, disebut <span style="color: green; font-weight: bold;">multilevel inheritance</span>.

- Java tidak mendukung <span style="color: green; font-weight: bold;">multiple inheritance</span>, yakni satu subclass memiliki <span style="color: green; font-weight: bold;">lebih dari satu</span> parent class.

</div>
</div>
</div>
