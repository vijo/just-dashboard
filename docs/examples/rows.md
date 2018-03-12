---
layout: default
title: How to use rows
---

# How to use rows
Here's an example code regarding the use of rows: 

```yaml
---
  dashboard "Example": 
    - 
      2 columns: 
        - 
          rows: 
            - 
              h2 text: "Lorem ipsum dolor sit amet"
            - 
              pie chart: 
                columns: 
                  - 
                    - "Apples"
                    - 3
                  - 
                    - "Oranges"
                    - 2
                  - 
                    - "Pears"
                    - 2
        - 
          rows: 
            - 
              h2 text: "Lorem ipsum dolor sit amet"
            - 
              p text: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dolor massa, luctus rhoncus justo vel, cursus placerat ligula. Proin pulvinar ipsum in enim rutrum, quis fermentum ex finibus. Nunc commodo urna tellus, tristique tempor magna tempor eget. Phasellus eu ex lacinia sapien viverra fermentum."

```
The code above will render a rows that looks like this:

![](../screenshots/rows.png)