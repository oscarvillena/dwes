+++
title = "Desarrollo de aplicaciones web"
date = 2021-09-28T17:04:36+02:00
weight = 5
chapter = true
pre = "<b>X. </b>"
+++

### Contenidos

# Ver el contenido del curso

![Texto alternativo](/images/daw-sp2.jpg)

Creacion de Hugo: 

En esta pagina se enseñara la creacion de una pagina estatica. En unos pasos faciles: 

{{% button href="https://es.wikieducator.org/Usuario:ManuelRomero" icon="fas fa-download" icon-position="right" %}}Wikieducator{{% /button %}}



{{%expand "Leer más..." %}}
Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
{{% /expand%}}

## Contenidos

{{<mermaid align="left">}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

## Contenidos

{{< mermaid >}}
gantt
        dateFormat  YYYY-MM-DD
        title Adding GANTT diagram functionality to mermaid
        section A section
        Completed task            :done,    des1, 2014-01-06,2014-01-08
        Active task               :active,  des2, 2014-01-09, 3d
        Future task               :         des3, after des2, 5d
        Future task2               :         des4, after des3, 5d
        section Critical tasks
        Completed task in the critical line :crit, done, 2014-01-06,24h
        Implement parser and jison          :crit, done, after des1, 2d
        Create tests for parser             :crit, active, 3d
        Future task in critical line        :crit, 5d
        Create tests for renderer           :2d
        Add to mermaid                      :1d
{{< /mermaid >}}

## Contenidos

{{< mermaid >}}
gitGraph:
options
{
  "nodeSpacing": 150,
  "nodeRadius": 10
}
end
  commit
  branch newbranch
  checkout newbranch
  commit
  commit
  checkout master
  commit
  commit
  merge newbranch
{{< /mermaid>}}

## Contenidos

{{% notice note %}}
Noticia
{{% /notice %}}

## Contenidos

{{< tabs >}}
{{% tab name="python" %}}
```python
print("Hello World!")
```
{{% /tab %}}
{{% tab name="R" %}}
```R
> print("Hello World!")
```
{{% /tab %}}
{{% tab name="Bash" %}}
```Bash
echo "Hello World!"
```
{{% /tab %}}
{{< /tabs >}}

## Contenidos

