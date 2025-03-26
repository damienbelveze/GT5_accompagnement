<!--

script:   https://unpkg.com/mermaid@9.1.1/dist/mermaid.min.js

@mermaid
<script run-once="true" modify="false">
mermaid.initialize({});

var svg = mermaid.render('io9wuwzxt',`@0`.replace(/\\n/g, "\n"),
function(g) {
    return true;
})

"HTML: " + svg
</script>
@end


@mermaid_eval
<script>
mermaid.initialize({});
var graphDefinition = `@input`
var cb = function(svgGraph) {
    return true;
}

var svg = mermaid.render('io9wuwzxt',graphDefinition,cb)
console.html(svg)
"LIA: stop"
</script>
@end

-->

# premier chapitre

            --{{1}}--
tgytyttyu

            --{{2}}--
yutyutyutyutyu


            



# deuxième chapitre

## premier paragraphe

Liste des planètes 

- Mercure  
- Jupiter  
- Mars  

![](https://commons.wikimedia.org/wiki/File:For%C3%AAt_de_Desvres_C%C3%A9p%C3%A9e_de_h%C3%AAtre_labellis%C3%A9e_%22Arbre_Remarquable_de_France%22.jpg)

![](https://commons.wikimedia.org/wiki/File:H%C3%AAtre_votif_dans_le_massif_du_ballon_d%27Alsace,_France.jpg)

Quel est le nombre de planètes du système solaire ?

[[ ]]  7
[[x]]  8
[[ ]]  9

- [[ ]] 

- [( )] not checked
- [(X)] checked

## deuxième paragraphe

```text
flowchart TD
    A[Christmas] -->|Get money| B(Go shopping)
    B --> C{Let me think}
    C -->|One| D[Laptop]
    C -->|Two| E[iPhone]
    C -->|Three| F[fa:fa-car Car]
```
@mermaid_eval

