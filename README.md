# html_css

## Arten von Styles bezüglich der Einbindung:
1. Externe Style Sheet 
1. Interne Style Sheet
1. Inline Styles

Im HTML-Code:
    &lt;p class="thick"&gt; This is a paragraph with class-style. &lt;/p&gt;

In der CSS-Datei:
    .thick {
    font-size:20px;
    }

bzw.

<p id="mySpecialPara"> This is a paragraph with id-style. Ids must be unique, that means you can have only one tag with this id-style!</p>

In der CSS-Datei:

#mySpecialPara {
   font-size:20px;
}

Inline-Variante:
<p style="font-size:20px;"> This is a paragraph. </p>
