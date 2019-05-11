---
title: "about"
layout: "pancakes"
stacks:
  - template: "section"
    id: "testID"
    class: "flex padding-bottom--xxl padding-top--xxls"
    rows:
    - template: "row"
      id:
      class: "flex container container--md padding-bottom--xxl"
      columns:
      - template: "column"
        id: "custom-id"
        class: "col-6"
        elements:
        - template: "text"
          html: | 
            <p>Text</p>
  - template: "section-2"
    id: "testID"
    class: "flex padding-top--xxl padding-bottom--xl"
    rows:
    - template: "row"
      id:
      class: "flex container container--md padding-bottom--xxl"
      columns:
      - template: "column"
        id: "custom-id"
        class: "col-6"
        elements:
        - template: "text"
          html: | 
            <p>Text 2</p> 
---
