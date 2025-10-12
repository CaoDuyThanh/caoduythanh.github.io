---
title: Learning QML — My Small Exercise Project
description: Examples of using QML on design UI.
author: thanhcao
date: 2019-08-10 11:33:00 +0700
categories: [UI/UX]
tags: [QML]
pin: true
math: true
mermaid: true
---

Recently, I’ve been exploring QML (Qt Modeling Language) — a declarative language used to build modern UI with Qt. I created a small repo called QML Exercises to get hands-on experience with QML basics and understand how components, bindings, and signals work together.

# Why QML?

QML allows you to describe UI declaratively — instead of manually updating layouts or styles, you define what you want, and QML handles the how. It’s quite similar to how HTML+CSS define structure and appearance but with reactive data binding like React or SwiftUI.

For example, a basic rectangle with animation looks like this:

```yaml
Rectangle {
    width: 200; height: 100
    color: "skyblue"

    MouseArea {
        anchors.fill: parent
        onClicked: parent.color = "lightgreen"
    }
}
```

Simple, clean, and reactive — no boilerplate C++ needed.

# What’s Inside the Repo

Each folder in the repo contains a small exercise focused on one QML concept:

- **Basic Elements** – experimenting with Rectangle, Text, and Image.
- **Layouts** – using Row, Column, and Grid to align components.
- **Bindings & Signals** – understanding how property updates flow automatically.
- **Animation** – playing with NumberAnimation and transitions.
- **Custom Components** – creating reusable .qml files to keep code modular.

Every exercise is small and self-contained — the goal isn’t to build an app, but to understand the language through doing it.

# What I Learned

QML is surprisingly expressive. You can build interactive, animated UI with minimal code. Some quick takeaways:

- **Declarative > Imperative**: describing state feels natural for UI.
- **Signal-slot model** still underpins QML, but bindings make it simpler.
- **Integration with C++** is powerful when needed, but you can go far with just QML.

# Next Step

I actually don't have any plan yet but knowing QML is useful tool to make desktop app later — maybe something like a media viewer or dashboard — to push beyond exercises into a real mini-project.

**Repo**: [QML-Exercises (GitHub)](https://github.com/CaoDuyThanh/QML-Exercises?tab=readme-ov-file).